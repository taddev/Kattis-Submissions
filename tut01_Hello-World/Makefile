# My Makefile for simple programs
# Using C++ compiler
CC=g++

# These CFLAGS are defined by Kattis so I'll make sure they Compile here also
CFLAGS=-g -O2 -static -std=gnu++0x

# Problem number
PROBLEM=tut01

all: $(PROBLEM)

$(PROBLEM): $(PROBLEM).cpp
	$(CC) $(CFLAGS) $(PROBLEM).cpp -o $(PROBLEM)

clean:
	rm -rf *.exe* $(PROBLEM) *.o