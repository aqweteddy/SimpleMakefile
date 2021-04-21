CFLAGS:=-Wall -g -O2
CC:=gcc
exe:=main.out

all: main.c f1.o f2.o
	${CC} ${CFLAGS} main.c f1.o f2.o -o ${exe}

$<: $*.c $*.h
	${CC} ${CFLAGS} -c $*.c -o $@

clean: 
	rm -f f2.o f1.o main.out
