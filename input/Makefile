.DEFAULT_GOAL := run

compile: input.f90
	gfortran input.f90 -o input
run: compile
	./input
clean: input
	rm input
