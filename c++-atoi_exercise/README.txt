Introduction

This assignment tests your abilities to code and build a simple C/C++ program.

In this test, I ask you to implement a program in main.cpp. The program should take
any number of integers as command line arguments and output the sum of them. E.g.:

./main.cpp 34 5 10
49
./main.cpp 12 2
14

In doing so, you normaly use the function atoi(const char* str) to convert from text to
integers. Please reimplement this function in myatoi.h/cpp.. While doing so please build
myatoi.h/cpp as shared library and link it into main.cpp. Use any build tool/scripts you
want with one rule: the build tool/scripts must be executable from the command line. E.g
you could write a Makefile or use CMake to generate one, or use any other command-line
build tool.

In summary:
1) get the project to build using a command-line build tool/script
2) reimplement the atoi-function in myatoi.h/cpp (not using the standard lib's atoi-function) 
   and build it as a shared library
3) link the library in main.cpp and implement the command-line arguments summation 
   program
