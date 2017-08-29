Sim03: data.o MemoryFunction.o
	g++ data.o MemoryFunction.o -o Sim03 -lpthread

data: data.cpp MemoryFunction.h
	g++ -c data.cpp -o data.o -lpthread

MemoryFunction: MemoryFunction.cpp MemoryFunction.h
	g++ -c MemoryFunction.cpp -o MemoryFunction.o

clean:
	\rm *.o Sim03
