CC=cc


all:	bin/hello

bin/hello:	hello.c
		mkdir -p $(@D) 
		$(CC) -o $@ $^

clean:
		rm -rf bin
