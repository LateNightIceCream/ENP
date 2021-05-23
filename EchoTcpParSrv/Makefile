CC = gcc
CFLAGS = -Wall
FUNCTIONS = writen.c readline.c

all: cli srv

cli:
	$(CC) $(CLFAGS) echotcpcli.c $(FUNCTIONS) -o cli

srv:
	$(CC) $(CLFAGS) echotcpsrv_par_a.c $(FUNCTIONS) -o srv
