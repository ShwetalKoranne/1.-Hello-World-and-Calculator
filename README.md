# 1.-Hello-World-and-Calculator

EXPERIMENT-1:- Aim: Hello World & Calculator Program.

Apparatus: VS Code or Programiz online compiler

Theory:

C++ is a powerful, general-purpose programming language developed as an extension of C. It supports both procedural and object-oriented programming, which makes it suitable for system/software development, game development, real-time simulations, and more.

Key Features:
Fast and efficient

Object-oriented (supports classes and objects)

Rich standard library

Allows low-level programming (memory management using pointers)


Single-line comments begin with // and stop at the end of the line.

The line int main() is the main function where program execution begins.
The line return 0; terminates main( )function and causes it to return the value 0 to the calling process.

int main() is the starting point of every C++ program.
main() is the function where execution begins.
int means the function will return an integer value.

The line return 0; terminates main( )function and causes it to return the value 0 to the calling process.

#include <iostream> is a preprocessor directive.

It tells the compiler to include the input-output stream library.

This library lets us use cout and cin for displaying and taking input.


using namespace std;
This line allows us to avoid writing std:: before standard names like cout, cin, etc.

std is the standard C++ namespace that includes all standard functions and classes. Without this line, you’d have to write:

std::cout << "Hello, World!";


Program1: This program demonstrates the basic structure of a C++ program and the use of the cout statement to display output on the screen.In this program, the #include preprocessor directive is used to include the standard input-output stream library which allows us to use cout and cin. The main() function is the entry point of every C++ program. Inside main(), the cout statement is used to print "Hello World" on the screen. The statement return 0; indicates that the program has ended successfully. This program helps beginners understand how to write, compile, and run a simple C++ program and how to display a message using cout.

Program2:This program accepts two floating-point numbers as input from the user and performs four basic arithmetic operations: addition, subtraction, multiplication, and division. First, two float variables Num1 and Num2 are declared to store user inputs. The cin statement is used to take input from the user. Then, the following operations are performed:

Addition: The two numbers are added and the result is stored in sum. 

Subtraction: The second number is subtracted from the first and stored in sub. 

Multiplication: Both numbers are multiplied and the result is stored in multi. 

Division: The first number is divided by the second number and the result is stored in div.

The results of each operation are displayed using cout. The use of the float data type ensures that decimal values are preserved in all calculations. This program helps to understand how to perform arithmetic operations in C++ and how to handle user input and output. It also demonstrates the importance of using appropriate data types to avoid loss of precision in calculations.

Conclusion: Hence, we were able to print hello world and build a basic calculator in C++.
