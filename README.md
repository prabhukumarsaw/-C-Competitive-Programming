**C++ Function question**

C++ Program for Linear search using recursion

C++ Program to Find Factorial of Number Using Recursion

C++ program to Find Sum of Natural Numbers using Recursion

C++ program to Check Number can Express as Sum of Prime Numbers

C++ Program to Check Prime Number

C++ Program to Display Prime Numbers Between Two Intervals

C++ Program to Find GCD Using Recursion

C++ Program to Find Power Using Recursion

C++ program to Reverse String Using Recursion

C++ Program to Convert Binary Number to Octal

C++Program to Convert Octal to Binary

C++ Program to Convert Octal Number to Decimal

C++ Program to Convert Decimal Number to Octal

C++ Program to Convert Binary Number to Decimal

C++ Program to convert decimal number to binary

C++ Program for Fibonacci Series Using Recursion

C++ program to swap values using pass by reference

C++ Program to print series using function: x + x^3/3! + x^5/5! +…….+ x^n/n!

C++ Program for Addition,subtraction and multiplication using function

C++ Program to find cube of number using function

C++ program to find greatest between two numbers using inline function

C++ program to find factorial by defining functions outside the class

C++ program to find greatest b/w 3 nos. by defining the functions inside class

C++ program to swap two characters and integers by call by value

C++ program to find reverse of number by defining functions outside class

C++ program to swap 2 characaters and integers by call by address

C++ program to find sum and product of 5 numbers using inline function

C++ program to add two time by Call by reference

C++ program to add two time by Call by address

C++ program to find how many times function called by objects

C++ program to find square of float and integer using inline function

C++ program to add two complex number passing objects as arguments

C++ program to find factorial of number using functions

C++ program to check number is palindrome or not using Function

C++ Program to Swap two numbers using call by value

C++ Program to Swap two numbers by call by address

C++ Program to Swap two numbers by call by reference



# -C-Competitive-Programming![cpp_core_guidelines_logo_text](https://user-images.githubusercontent.com/54577120/154421574-7dc815a7-5986-4181-9c76-c8e600762f57.png)

**Functions in C/C++**
 A function is a set of statement that takes input, do some specific compution and produce output.
 why used- some task are commonly or repeatedly so make a function instead of writing the same code again and again if need output call the function.
 <>
  
 #include <iostream>
using namespace std;
  
int max(int x, int y) 
{ 
    if (x > y) 
    return x; 
    else
    return y; 
} 
  
int main() {
    int a = 10, b = 20; 
  
    // Calling above function to find max of 'a' and 'b' 
    int m = max(a, b); 
  
    cout << "m is " << m; 
    return 0; 
}
  </>
**Pass by Value:**
  In this parameter passing method, values of actual parameters are copied to function’s formal parameters and the two types of parameters are stored in different memory locations. So any changes made inside functions are not reflected in actual parameters of caller.
  
**Pass by Reference:**
  
  Both actual and formal parameters refer to same locations, so any changes made inside the function are actually reflected in actual parameters of caller.
  
  
  
 **Object Oriented Programming in C++** 
  
  
