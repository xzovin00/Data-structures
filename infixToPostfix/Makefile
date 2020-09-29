
PRJ=c204
#
STACKPATH=../stack/
PROGS=$(PRJ)-test
CC=gcc
CFLAGS=-Wall -std=c99 -pedantic -lm -I$(STACKPATH)

all: $(PROGS)

$(PRJ)-test: $(PRJ).c $(PRJ)-test.c $(STACKPATH)c202.c
	$(CC) $(CFLAGS) -o $@ $(PRJ).c $(PRJ)-test.c $(STACKPATH)c202.c

clean:
	rm -f *.o *.out $(PROGS)
#