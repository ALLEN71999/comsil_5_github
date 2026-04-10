animal_exe : dog.o blackcow.o turtle.o main.o
	gcc -o animal_exe dog.o blackcow.o turtle.o main.o

dog.o : dog.c animal.h
	gcc -c -o dog.o dog.c

blackcow.o : blackcow.c animal.h
	gcc -c -o blackcow.o blackcow.c

turtle.o : turtle.c animal.h
	gcc -c -o turtle.o turtle.c

main.o : main.c animal.h
	gcc -c -o main.o main.c

clean :
	rm *.o animal_exe
