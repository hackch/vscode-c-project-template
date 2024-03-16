CC =			gcc
CFLAGS =		-g -O0 -I.
OBJ =			MyProgram.o
PROGNAME =		MyProgram.exe

%.o:			%.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)

default:		$(PROGNAME)

$(PROGNAME):	$(OBJ)
	$(CC) -o $@ $^ $(CFLAGS)

clean:
	-rm -f 	*~ *% *.o core