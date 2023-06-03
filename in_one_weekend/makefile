all: main.cpp
	mkdir -p build
	clang++ -Wall -std=c++11 main.cpp -o build/main

run: all
	./build/main > build/test.ppm && open build/test.ppm
