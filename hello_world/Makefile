.DEFAULT_GOAL := run

compile: hello_world.f90
	gfortran hello_world.f90 -o hello_world
run: compile
	./hello_world
clean: hello_world
	rm hello_world
