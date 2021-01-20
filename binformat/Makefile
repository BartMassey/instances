BINS = asc2bin bin2asc showpreamble

all: $(BINS)

asc2bin: asc2bin.c genbin.h
	$(CC) $(CFLAGS) asc2bin.c -o asc2bin 

bin2asc: bin2asc.c genbin.h
	$(CC) $(CFLAGS) bin2asc.c -o bin2asc 

showpreamble: showpreamble.c
	$(CC) $(CFLAGS) showpreamble.c -o showpreamble 

clean:
	-rm -f $(BINS)
