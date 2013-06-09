main: main.o md5.o
	gcc main.o md5.o -o main
main.o: main.c
	gcc -c main.c
md5.o: md5.c md5.h
	gcc -c md5.c
clean:
	rm *.o
