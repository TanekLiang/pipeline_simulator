test: cpu_sim.py test.exe
	./cpu_sim.py test.exe

test.exe: test.s compiler.py
	./compiler.py test.s > test.exe

clean:
	rm test.exe

.PHONY: test clean
