#!makefile

all: test.out

test.out: main.c
	gcc -I/opt/rocm/hsa/include/hsa -o $@ $< -L/opt/rocm/lib -lhsa-runtime64

clean:
	rm *.o *.out
