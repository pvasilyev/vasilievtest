default: clean program

clean:
	rm -f *.o program

2.o: 2.cpp
	g++ -c 2.cpp -Wall

program: 2.o
	g++ 2.o -o program -Wall
