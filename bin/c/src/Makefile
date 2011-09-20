# build carserver executable when user executes "make"
carserver: carserver.o
	$(CC) $(LDFLAGS) carserver.o -o carserver
carserver.o: carserver.c
	$(CC) $(CFLAGS) -c carserver.c

# remove object files and executable when user executes "make clean"
clean:
	rm *.o carserver


