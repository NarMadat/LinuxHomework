CXX = g++
CXXFLAGS = -Wall -std=c++20

all: Complex_operations

Complex_operations: main.o complex.o sort.o
	$(CXX) $(CXXFLAGS) -o Complex_operations main.o complex.o sort.o


main.o: main.cpp complex.h sort.h
	$(CXX) $(CXXFLAGS) -c main.cpp

complex.o: complex.cpp complex.h
	$(CXX) $(CXXFLAGS) -c complex.cpp

sort.0: sort.cpp sort.h complex.h
	$(CXX) $(CXXFLAGS) -c sort.cpp

clean:
	rm -f *.o Complex_operations



