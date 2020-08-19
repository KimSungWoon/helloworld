
hello : hello.o main.o
	gcc - hello hello.o main.o

hello.o : hello.c
	gcc -c hello.c

main.o : main.c
	gcc -c main.c

clean:
	rm -f*.o hello

