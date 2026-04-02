CC = gcc
CFLAGS = -Wall -g -std=c23 -pedantic-errors

all: hello.exe

hello.exe: hello.c
	$(CC) $(CFLAGS) hello.c -o hello.exe

run: hello.exe
	./hello.exe

clean:
	rm -f hello.exe 

