CC=gcc
prefix=/usr/local

idiotshell: idiotshell.c
	$(CC) $(CFLAGS) $(LFLAGS) idiotshell.c -o idiotshell

install:
	install -m 0755 idiotshell $(prefix)/bin
	install -m 0755 roll.sh $(prefix)/bin

clean:
	rm -f idiotshell

.PHONY: idiotshell install clean
