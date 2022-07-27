CC = g++
CFLAGS = -I/opt/tvm/include/

LDIR = /opt/tvm/build/
LIB = -ltvm -ltvm_runtime

add2: add2.cpp
	$(CC) -o add2.o -L$(LDIR) $(CFLAGS) add2.cpp

clean:
	rm -f ./*.o