<!--
author:   U. Anthony Omegbu
email:    anthonyomegbu@gmail.com
version:  0.0.1

tags:     LiaScript, education, OER

logo:     https://your-logo-url.com/logo.jpg

comment:  This document is a simple LiaScript course example.

-->

Sure, here's a study guide for C++ based on the outline provided:

# C++ Study Guide

## I. Introduction

C++ is a powerful and versatile programming language that was first developed in the 1980s. It is widely used in a variety of applications, including operating systems, video games, and scientific simulations.

A. Overview of C++

C++ is a general-purpose programming language that supports object-oriented programming (OOP) and provides low-level memory manipulation features. It is an extension of the C programming language and includes additional features such as templates, exceptions, and the Standard Template Library (STL).

B. Brief history of C++

C++ was first developed by Bjarne Stroustrup at Bell Labs in the early 1980s. It was initially called "C with Classes" and was designed to add object-oriented features to the C programming language. The first commercial implementation of C++ was released in 1985.

C. Advantages of C++

C++ has several advantages over other programming languages, including:

Performance: C++ is a compiled language that generates efficient machine code, making it well-suited for applications that require high performance.
Flexibility: C++ supports both procedural and object-oriented programming paradigms, allowing programmers to choose the best approach for a given task.
Portability: C++ code can be compiled and run on a wide range of hardware and operating systems.
Community: C++ has a large and active community of developers who contribute to open-source projects and provide support through forums and user groups.
D. Applications of C++

C++ is used in a wide range of applications, including:

Operating systems: C++ is used to develop parts of many operating systems, including Windows, macOS, and Linux.
Video games: C++ is a popular choice for game development due to its high performance and low-level control over hardware.
Scientific simulations: C++ is often used to develop simulations of complex physical systems, such as weather patterns or molecular dynamics.
Financial systems: C++ is used in high-frequency trading and other financial applications that require fast and accurate processing of large amounts of data.

## II. Basic Concepts of C++

To understand C++, it is important to first understand some of its basic concepts.

A. Variables

A variable is a named storage location in memory that holds a value. In C++, variables must be declared with a data type and can be assigned a value using the assignment operator "=".

B. Data Types

C++ supports several built-in data types, including integers, floating-point numbers, characters, and booleans. It also allows programmers to define their own data types using structures and classes.

C. Operators

C++ supports a variety of operators for performing arithmetic, logical, and bitwise operations. These include addition, subtraction, multiplication, division, and more.

D. Control Structures

Control structures allow programmers to control the flow of execution in a program. C++ supports several control structures, including if-else statements, switch statements, and loops.

E. Functions

Functions are blocks of code that perform a specific task. They can be called from other parts of a program and can return a value.

F. Arrays

Arrays are collections of variables that have the same data type. They are indexed by integers and can be used to store multiple values of the same type.

## C++ Variables, Data Types, and Constants Study Guide

Variables

A variable is a container that holds a value, such as a number or a piece of text. In C++, we use variables to store data that we want to use in our programs. We can think of a variable like a storage box where we can put things in and take them out whenever we need them.

To declare a variable in C++, we start by specifying its data type, followed by the variable name. For example, to declare a variable to store an integer value, we use the int data type:

```cpp
int myInteger;
```

This code declares a variable named myInteger with the integer data type. The variable is currently uninitialized, which means it doesn't have a value assigned to it yet.

To assign a value to a variable, we use the assignment operator =. For example, if we want to assign the value 10 to myInteger, we can do it like this:

```cpp
myInteger = 10;
```

We can also declare and initialize a variable at the same time. Here's an example:

```cpp
int myOtherInteger = 20;
```

This code declares a new variable named myOtherInteger with the integer data type, and initializes it with the value 20.

Data Types

In C++, every variable has a data type, which tells the computer what kind of value it's storing. There are several data types available in C++, including:

Integers (int): used to store whole numbers (e.g. 1, 2, 3).
Floating-point numbers (float and double): used to store numbers with decimal places (e.g. 3.14, 2.5).
Characters (char): used to store single characters (e.g. 'a', 'b', 'c').
Booleans (bool): used to store logical values (true or false).

To declare a variable with a specific data type, we use the appropriate keyword before the variable name. For example, to declare a variable to store a floating-point value, we use the float data type:

```cpp
float myFloat;
```

This code declares a variable named myFloat with the floating-point data type. The variable is currently uninitialized.

We can also declare and initialize a variable with a specific data type at the same time. Here's an example:

```cpp
char myChar = 'a';
```

This code declares a variable named myChar with the character data type, and initializes it with the value 'a'.

Constants

A constant is a value that cannot be changed once it has been assigned. We can think of a constant like a number that is set in stone. In C++, we use constants to represent values that should never change, such as the value of pi or the number of seconds in a minute.

To declare a constant in C++, we use the const keyword before the data type. For example, to declare a constant to represent the value of pi, we can do it like this:

```cpp
const double PI = 3.14159265359;
```

This code declares a constant named PI with the double precision floating-point data type, and initializes it with the value 3.14159265359.

Example

Here's an example of how variables, data types, and constants work together in C++. Let's say we want to write a program that calculates the area of a rectangle. We'll need two variables to store the length and width of the rectangle. We can use the integer data type for these variables because they represent whole numbers. We can also use constants to represent the formula for calculating the area:

```cpp
const int LENGTH = 5;
const int WIDTH = 3;
int area = LENGTH * WIDTH;
```

In this code, we're using two constants, LENGTH and WIDTH, to represent the dimensions of the rectangle. We're also using the integer data type for the area variable because the area of a rectangle is always a whole number. We're calculating the area by multiplying the LENGTH and WIDTH variables together, and storing the result in the area variable.

Conclusion

In summary, variables, data types, and constants are fundamental elements of C++ programming. We use variables to store data, data types to specify the type of data we're storing, and constants to represent values that should never change. By understanding these concepts, we can create more robust and efficient programs in C++.

## C++ Programming Basics Study Guide

This study guide is designed to introduce you to the basics of programming in C++. We'll cover the following topics:

**Comments**
**Algorithms**
**White Space**
**Abstraction**
**Skeleton Program**

1. Comments

Comments are used to document your code, explain its purpose, and make it easier to understand for yourself and others. In C++, comments start with // for single-line comments and /* */ for multi-line comments. Here's an example:

```cpp
// This is a single-line comment in C++

/* This is a
   multi-line comment */
```
2. Algorithms

An algorithm is a set of steps that solve a specific problem. In programming, algorithms are typically implemented as functions. Here's an example of a function that finds the maximum of two numbers:

```cpp
int max(int a, int b) {
  if (a > b) {
    return a;
  } else {
    return b;
  }
}
```
3. White Space

White space refers to the spaces, tabs, and newlines that separate code elements in your program. In C++, white space is used to make your code more readable and easier to understand. Here's an example:

```cpp
int main() {
  int x = 5;
  int y = 10;
  int z = x + y;
  std::cout << "The sum of " << x << " and " << y << " is " << z << std::endl;
  return 0;
}
```
4. Abstraction

Abstraction is the process of hiding implementation details and exposing only the necessary information to the user. In C++, you can use classes and objects to implement abstraction. Here's an example:

```cpp
class Rectangle {
  private:
    int width;
    int height;
  public:
    Rectangle(int w, int h) {
      width = w;
      height = h;
    }
    int area() {
      return width * height;
    }
};

int main() {
  Rectangle r(5, 10);
  std::cout << "The area of the rectangle is " << r.area() << std::endl;
  return 0;
}
```
5. Skeleton Program

A skeleton program is a basic program that contains only the necessary components to compile and run. In C++, a skeleton program typically includes the main function, standard input/output headers, and a return statement. Here's an example:

```cpp
#include <iostream>

int main() {
  std::cout << "Hello, World!" << std::endl;
  return 0;
}
```

This is a basic C++ program that prints "Hello, World!" to the console. It includes the iostream header for input/output operations and the main function, which is the entry point of the program. The return 0; statement indicates that the program has run successfully.

Conclusion

These are the basics of programming in C++. By understanding these concepts, you'll be able to write simple programs and start exploring more advanced topics. Keep practicing and experimenting with code to improve your skills!

## III. Object-Oriented Programming in C++

C++ is an object-oriented programming (OOP) language, which means it supports the creation of objects that encapsulate data and behavior.

A. Classes and Objects

Classes are templates for creating objects, and objects are instances of a class. Classes can have data members and member functions, which are accessed using the dot operator.

B. Encapsulation

Encapsulation is the practice of hiding the implementation details of a class from outside code. In C++, this is achieved by using access modifiers such as public, private, and protected.

C. Inheritance

Inheritance is a way to create new classes from existing ones by inheriting their properties and methods. In C++, this is achieved using the "extends" keyword.

D. Polymorphism

Polymorphism allows objects to take on different forms or behaviors depending on the context. In C++, this is achieved using virtual functions and function overloading.

E. Abstraction

Abstraction is the practice of simplifying complex systems by hiding unnecessary details. In C++, this is achieved through the use of abstract classes and interfaces.

## IV. Advanced C++ Concepts

C++ includes several advanced features that allow programmers to write more powerful and efficient code.

A. Templates

Templates allow for generic programming by defining functions or classes that can work with any data type. This can improve code reusability and reduce the amount of duplicate code.

B. Exception Handling

Exception handling is a way to handle errors and exceptions that may occur during program execution. In C++, this is achieved using try-catch blocks.

C. STL (Standard Template Library)

The Standard Template Library (STL) is a collection of classes and algorithms that provide useful data structures and functions for common programming tasks.

D. Multithreading

Multithreading allows a program to perform multiple tasks simultaneously, improving performance and responsiveness. In C++, this is achieved using threads and synchronization mechanisms.

E. File Handling

File handling is the process of reading and writing data to files on disk. C++ provides several classes and functions for file input/output operations.

F. Pointers and References

Pointers and references allow programmers to work with memory directly, which can be useful for low-level programming and performance optimization.

V. C++ Development Environment

To write and run C++ programs, you will need a development environment that includes a C++ compiler, an IDE, and a debugger.

A. C++ compilers

A compiler is a program that translates source code into machine code that can be executed by a computer. There are several C++ compilers available, including GCC and Clang.

B. Integrated Development Environments (IDEs)

An IDE is a software application that provides a comprehensive environment for writing, debugging, and testing code. Popular C++ IDEs include Visual Studio, Code::Blocks, and Eclipse.

C. Debuggers

A debugger is a tool that allows programmers to step through code and inspect variables to identify and fix errors. C++ debuggers include GDB and Visual Studio Debugger.

## VI. Best Practices for C++ Programming

To write effective and maintainable C++ code, it is important to follow best practices.

A. Code Organization

Well-organized code is easier to understand and maintain. Use meaningful variable and function names, and group related code together in functions or classes.

B. Error Handling

Make sure to handle errors and exceptions properly, and use appropriate error messages and logging to help diagnose issues.

C. Memory Management

C++ provides low-level control over memory, but this also means that programmers must be careful to avoid memory leaks and undefined behavior.

D. Optimization

C++ is a high-performance language, but this also means that poorly optimized code can have a significant impact on performance. Use profiling tools and optimization techniques to improve performance.

E. Coding Style

Consistent and readable code is easier to understand and maintain. Use a consistent coding style and follow established guidelines such as the Google C++ Style Guide.

## VII. Conclusion

C++ is a powerful and versatile programming language that offers a range of features for developing efficient and scalable applications. Whether you are building operating systems, video games, scientific simulations, or financial systems, C++ provides the tools you need to get the job done.

To become proficient in C++, it is important to have a strong foundation in the basic concepts and principles of the language, as well as an understanding of advanced topics such as OOP, templates, and multithreading. It is also important to develop good coding practices, such as organizing code effectively, handling errors properly, and optimizing for performance.

By following these principles and using the right tools, you can become a skilled C++ programmer and develop robust and efficient applications.

# Study Guide: Comparing Linear Search and Binary Search


```cpp
#include <iostream>
#include <ctime>
#include <cstdlib>

using namespace std;

int linear_search(int arr[], int size, int target) {
    for (int i = size - 1; i >= 0; i--) {
        if (arr[i] == target) {
            return size - i;
        }
    }
    return -1;
}

int binary_search(int arr[], int size, int target) {
    int left = 0;
    int right = size - 1;
    int guesses = 0;

    while (left <= right) {
        guesses++;
        int mid = left + (right - left) / 2;

        if (arr[mid] == target) {
            return guesses;
        }

        if (arr[mid] < target) {
            left = mid + 1;
        } else {
            right = mid - 1;
        }
    }
    return guesses;
}

int main() {
    const int array_size = 1000019;
    int arr[array_size];

    for (int i = 0; i < array_size; i++) {
        arr[i] = array_size - i - 1;
    }

    srand(time(0));
    int target = rand() % array_size;

    int linear_loops = linear_search(arr, array_size, target);
    int binary_guesses = binary_search(arr, array_size, target);

    cout << "[Linear Vs. Binary Search]\n";
    cout << "The target value is " << target << endl;
    cout << "Linear Search: " << linear_loops << " loop(s)\n";
    cout << "Binary Search: " << binary_guesses << " guess(es)\n";

    if (linear_loops < binary_guesses) {
        cout << "Linear Search is faster this time!\n";
    } else if (binary_guesses < linear_loops) {
        cout << "Binary Search is faster this time!\n";
    } else {
        cout << "It's a tie!\n";
    }

    return 0;
}
```

In this guide, we will dissect a C++ code that compares the performance of linear search and binary search algorithms on a sorted array. Think of this as a race between two people, one who checks every participant in a race one by one (linear search) and another who eliminates half the participants in every step (binary search).

Code Overview

The code consists of three main components:

linear_search function
binary_search function
main function

Let's go through each component line by line.

Import Libraries

```cpp
#include <iostream>
#include <ctime>
#include <cstdlib>

```

We include the necessary libraries. iostream for input/output, ctime for time-related functions, and cstdlib for random number generation.

Using Namespace

```cpp
using namespace std;
```

Using the std namespace for convenience.

**Linear Search Function**

```cpp
int linear_search(int arr[], int size, int target) {
    for (int i = size - 1; i >= 0; i--) {
        if (arr[i] == target) {
            return size - i;
        }
    }
    return -1;
}
```

This function takes an array, its size, and the target value to search for. It starts from the end of the array and iterates backwards, checking if the current element is equal to the target value. If found, it returns the number of loops required. If not found, it returns -1.

**Binary Search Function**

```cpp
int binary_search(int arr[], int size, int target) {
    int left = 0;
    int right = size - 1;
    int guesses = 0;

    while (left <= right) {
        guesses++;
        int mid = left + (right - left) / 2;

        if (arr[mid] == target) {
            return guesses;
        }

        if (arr[mid] < target) {
            left = mid + 1;
        } else {
            right = mid - 1;
        }
    }
    return guesses;
}
```

This function also takes an array, its size, and the target value to search for. It starts with two pointers, left and right, and keeps track of the number of guesses made. It calculates the midpoint and compares it to the target value. If the midpoint is equal to the target, it returns the number of guesses. If the midpoint is less than the target, it updates the left pointer; otherwise, it updates the right pointer.

**Main Function**

```cpp
int main() {
    const int array_size = 1000019;
    int arr[array_size];

    for (int i = 0; i < array_size; i++) {
        arr[i] = array_size - i - 1;
    }
}
```


We start by defining the size of the array (1,000,019) and initialize the array. We then fill the array in reverse order.

```cpp
    srand(time(0));
    int target = rand() % array_size;
```

We seed the random number generator with the current time and generate a random target value within the bounds of the array.

```cpp
    int linear_loops = linear_search(arr, array_size, target);
    int binary_guesses = binary_search(arr, array_size, target);
```

We call the linear_search and binary_search functions and store the results.

```cpp
    cout << "[Linear Vs. Binary Search]\n";
    cout << "The target value is " << target << endl;
    cout << "Linear Search: " << linear_loops << " loop(s)\n";
    cout << "Binary Search: " << binary_guesses << " guess(es)\n";
```

We display the target value, the number of loops for linear search, and the number of guesses for binary search.

```cpp
    if (linear_loops < binary_guesses) {
        cout << "Linear Search is faster this time!\n";
    } else if (binary_guesses < linear_loops) {
        cout << "Binary Search is faster this time!\n";
    } else {
        cout << "It's a tie!\n";
    }
```

We compare the number of loops and guesses to determine which algorithm was faster and print the result. If the number of loops and guesses are equal, we print that it's a tie.

```cpp
    return 0;
}
```

Finally, we return 0 to signal the successful execution of the program.

Summary

This code demonstrates the performance difference between linear search and binary search on a sorted array. Linear search checks each element one by one, while binary search eliminates half of the remaining elements with each step. By comparing the number of loops and guesses, we can see which algorithm is faster for a particular target value.
      

## FAQ Study Guide

Why is there a -1 in this part?

```cpp
for (int i = 0; i < array_size; i++) {
    arr[i] = array_size - i - 1;
}
```

The -1 in the code is used to initialize the elements of the arr array with values in descending order. The expression array_size - i - 1 is used to assign values to the array elements starting from array_size - 1 and decrementing down to 0. This is because the loop variable i starts from 0 and goes up to array_size - 1, so by subtracting i and then -1 from array_size, we get the values we need to fill the array in descending order. This initialization is done to simulate an unsorted array with arbitrary integer values, which can be used to test the linear and binary search functions.

Why is there a zero in this part?

```cpp
srand(time(0));
```

The time(0) function call returns the current time as the number of seconds since January 1, 1970, also known as the Unix epoch. The srand function uses this value as the seed for the random number generator. The 0 passed as an argument to time() is an optional parameter that specifies a pointer to a time_t object to receive the current time. If this parameter is set to 0 or NULL, the function simply returns the time as a time_t value instead of storing it in a variable.

In this case, the value of time(0) is being used directly as the seed for the random number generator, so there is no need to store it in a variable. This is a common idiom in C++ for obtaining a "random" seed based on the current time, which can be used to initialize a random number generator for use in simulations, games, or other applications.

What is a random number generator?

A random number generator is a computer program that generates a sequence of numbers that appear to be random, but are actually determined by a mathematical algorithm. In programming, we can use a random number generator to simulate events that have an element of chance or unpredictability, such as rolling dice or shuffling cards. To make the random number generator produce different sequences of numbers each time we run our program, we need to give it a different starting point, called a "seed."

What is a seed in a random number generator?

A seed is a starting point for a random number generator. The seed determines the sequence of random numbers that the generator will produce. By changing the seed, we can get a different sequence of random numbers. One common way to set the seed is to use the current time, since the time is always changing. In C++, we can use the srand function to set the seed for the random number generator. By calling srand with a different seed value each time we run our program, we can get a different sequence of random numbers.


# Study Guide: Implementing Random Sort Algorithm

```cpp
#include <iostream>
#include <ctime>
#include <cstdlib>

using namespace std;

bool check_if_sorted(int arr[], int size) {
    for (int i = 1; i < size; i++) {
        if (arr[i - 1] > arr[i]) {
            return false;
        }
    }
    return true;
}

void shuffleArray(int arr[], int size) {
    for (int i = size - 1; i > 0; i--) {
        int j = rand() % (i + 1);
        swap(arr[i], arr[j]);
    }
}

void printArray(int arr[], int size) {
    for (int i = 0; i < size; i++) {
        cout << arr[i];
        if (i < size - 1) {
            cout << ", ";
        }
    }
    cout << endl;
}

int main() {
    srand(time(0));

    const int array_size = 17;
    int arr[array_size];

    for (int i = 0; i < array_size; i++) {
        arr[i] = rand() % 359 + 1;
    }

    int attempts = 0;

    cout << "[Random Sort]" << endl;

    while (!check_if_sorted(arr, array_size)) {
        cout << "Printing array..." << endl;
        printArray(arr, array_size);

        cout << "Not sorted yet!" << endl;
        cout << "Shuffling array..." << endl;
        shuffleArray(arr, array_size);

        attempts++;
    }

    cout << "Printing array..." << endl;
    printArray(arr, array_size);

    cout << "Hooray, it's sorted! And it only took " << attempts << " attempts!" << endl;

    return 0;
}
```

In this guide, we will go through the process of creating a simple program to implement the Random Sort algorithm on a randomly generated array. The program will consist of the following components:

check_if_sorted function

shuffleArray function

printArray function

main function

Code Overview

Let's start by creating each function one by one.

Check If Sorted Function

```cpp
bool check_if_sorted(int arr[], int size) {
    for (int i = 1; i < size; i++) {
        if (arr[i - 1] > arr[i]) {
            return false;
        }
    }
    return true;
}
```

This function checks if the given array is sorted in non-descending order. It takes an array and its size as input and returns a boolean value. If the array is sorted, it returns true, otherwise false.

Shuffle Array Function

```cpp

void shuffleArray(int arr[], int size) {
    for (int i = size - 1; i > 0; i--) {
        int j = rand() % (i + 1);
        swap(arr[i], arr[j]);
    }
}
```

This function shuffles the given array using the Fisher-Yates algorithm. It takes an array and its size as input and modifies the original array in place.

Print Array Function


```cpp
void printArray(int arr[], int size) {
    for (int i = 0; i < size; i++) {
        cout << arr[i];
        if (i < size - 1) {
            cout << ", ";
        }
    }
    cout << endl;
}
```

This function prints the contents of the given array. It takes an array and its size as input and prints the array elements separated by commas.

Main Function


```cpp
int main() {
    srand(time(0));

    const int array_size = 17;
    int arr[array_size];

    for (int i = 0; i < array_size; i++) {
        arr[i] = rand() % 359 + 1;
    }

    int attempts = 0;

    cout << "[Random Sort]" << endl;

    while (!check_if_sorted(arr, array_size)) {
        cout << "Printing array..." << endl;
        printArray(arr, array_size);

        cout << "Not sorted yet!" << endl;
        cout << "Shuffling array..." << endl;
        shuffleArray(arr, array_size);

        attempts++;
    }

    cout << "Printing array..." << endl;
    printArray(arr, array_size);

    cout << "Hooray, it's sorted! And it only took " << attempts << " attempts!" << endl;

    return 0;
}
```

In the main function, we first seed the random number generator with the current time. We then create an array of size 17 and fill it with random numbers between 1 and 359. We initialize a variable to count the number of shuffle attempts.

We use a while loop to check if the array is sorted using the check_if_sorted function. If it's not sorted, we print the array, shuffle it using the shuffleArray function, and increment the attempts counter. We repeat this process until the array is sorted.

Finally, we print the sorted array and display the number of attempts it took to sort the array using the Random Sort algorithm.

Summary

This code demonstrates the implementation of the Random Sort algorithm on a randomly generated array. The algorithm repeatedly shuffles the array and checks if it's sorted. The worst-case time complexity of this algorithm is O(∞), as it could potentially take an infinite number of attempts to sort the array. This simple program helps illustrate the inefficiency of the Random Sort algorithm compared to other sorting algorithms like Bubble Sort, Selection Sort, and Insertion Sort. The program uses three helper functions: check_if_sorted, shuffleArray, and printArray, to carry out the sorting process and display the intermediate results.

# FAQ Study Guide: Random Sort Program

## Q1: Why is `int i = 1` and not `0` in the `check_if_sorted` function?

A1: In the `check_if_sorted` function, the loop iterates over the elements of the array, starting from index 1 and comparing it to the previous element at index i-1. If i is initialized to 0, then when the loop attempts to access the element at index i-1, it will access an invalid memory location, which can cause undefined behavior. Therefore, the loop starts from index 1 to ensure that there is a valid previous element to compare against. The first element of the array at index 0 will be compared to the second element at index 1.

## Q2: Where does the `-1` come from, and why is the condition `i > 0` in the shuffleArray function?

A2: This line of code is part of the `shuffleArray` function, which shuffles the elements of an integer array randomly. The for loop starts from the last element of the array (i = size - 1), and iterates backwards to the second element (i > 0), swapping each element with a randomly selected element from the remaining unshuffled elements.

The `-1` is used to make sure that we start the loop from the last element of the array, since the index of the last element is always one less than the size of the array. For example, if the size of the array is 5, then the last element is at index 4 (since arrays are zero-indexed).

The `i > 0` condition is used to make sure that we stop the loop after swapping the second element, and not the first element. This is because we don't need to swap the first element with itself, and swapping it would not change anything. If we didn't have this condition, the loop would also swap the first element with a randomly selected element, which is unnecessary.

## Q3: Is `swap` a restricted keyword in C++?

A3: `swap()` is a function provided by the C++ Standard Library that swaps the values of two variables. It is not a restricted keyword in C++, but it is a predefined function that is part of the C++ Standard Library.

In the given program, `swap(arr[i], arr[j])` is used to swap the values of two elements in the `arr` array. The `i` and `j` variables represent the indices of the elements to be swapped.

## Q4: What is the purpose of `+1` in `rand() % (i + 1)`?

A4: The `rand()` function generates a random integer between 0 and a maximum value determined by the implementation. In this program, we want to use `rand()` to generate a random index between 0 and `i`, where `i` is the current index of the element being shuffled in the `shuffleArray` function.

However, the `%` operator in C++ computes the remainder of a division operation. So if we use `rand() % i` to generate a random index, the possible range of indices would be from 0 to `i - 1`, which is not what we want. To include the upper bound value of `i` in the possible range of indices, we add 1 to `i` when computing the maximum value for the `%` operator.

The `+1` in the `rand() % (i + 1)` expression is used to make sure that the randomly generated index includes the current element being shuffled. This ensures that each element has an equal chance of being swapped with any other un


# Study Guide for Overloaded Surprise Function Code

```cpp
#include <iostream>
#include <string>
#include <cmath>

using namespace std;

int surprise_function(int a, int b) {
    return a + b;
}

float surprise_function(float a, float b) {
    return a / b;
}

double surprise_function(double a, double b) {
    return fmod(a, b);
}

string surprise_function(char a, char b) {
    return string(1, a) + b;
}

bool surprise_function(bool a, bool b) {
    return a && b;
}

int main() {
    cout << "[Overloaded Surprise Function]" << endl;
    cout << "What data type do you want to enter? ";
    string data_type;
    cin >> data_type;

    cout << "Value #1: ";
    if (data_type == "int") {
        int a, b;
        cin >> a;
        cout << "Value #2: ";
        cin >> b;
        cout << "Calling surprise_function()..." << endl;
        cout << "The result is " << surprise_function(a, b) << endl;
    } else if (data_type == "float") {
        float a, b;
        cin >> a;
        cout << "Value #2: ";
        cin >> b;
        cout << "Calling surprise_function()..." << endl;
        cout << "The result is " << surprise_function(a, b) << endl;
    } else if (data_type == "double") {
        double a, b;
        cin >> a;
        cout << "Value #2: ";
        cin >> b;
        cout << "Calling surprise_function()..." << endl;
        cout << "The result is " << surprise_function(a, b) << endl;
    } else if (data_type == "char") {
        char a, b;
        cin >> a;
        cout << "Value #2: ";
        cin >> b;
        cout << "Calling surprise_function()..." << endl;
        cout << "The result is " << surprise_function(a, b) << endl;
    } else if (data_type == "boolean") {
        bool a, b;
        cin >> boolalpha >> a;
        cout << "Value #2: ";
        cin >> boolalpha >> b;
        cout << "Calling surprise_function()..." << endl;
        cout << boolalpha << "The result is " << surprise_function(a, b) << endl;
    } else {
        cout << "Invalid data type entered." << endl;
    }

    return 0;
}
```

This code demonstrates the use of overloaded functions in C++. The program takes in two values of a specified data type, performs different operations depending on the data type, and prints the result.

Components and Line-by-Line Explanation

Include necessary headers:

```cpp
#include <iostream>
#include <string>
```

These headers provide the input/output stream (iostream) and string manipulation functionality (string) required for this code.

Define surprise_function for different data types:

```cpp
int surprise_function(int a, int b) {
    return a + b;
}

float surprise_function(float a, float b) {
    return a / b;
}

double surprise_function(double a, double b) {
    return fmod(a, b);
}

string surprise_function(char a, char b) {
    return string(1, a) + b;
}

bool surprise_function(bool a, bool b) {
    return a && b;
}
```

These functions perform different operations based on the data type of the input values:

int: addition

float: division

double: modulus (remainder)

char: concatenation (return as string)

bool: result of AND


main() function:

```cpp
int main() {
    cout << "[Overloaded Surprise Function]" << endl;
    cout << "What data type do you want to enter? ";
    string data_type;
    cin >> data_type;
```

The program first prompts the user to enter the data type they want to use.

Based on the data type, the program prompts the user for two values and calls the corresponding surprise_function:

```cpp
    cout << "Value #1: ";
    if (data_type == "int") {
        int a, b;
        cin >> a;
        cout << "Value #2: ";
        cin >> b;
        cout << "Calling surprise_function()..." << endl;
        cout << "The result is " << surprise_function(a, b) << endl;
    } //... Other data types follow a similar pattern
```

The program checks the user's input for the data type and prompts the user to enter two values of that type. Then, it calls the appropriate surprise_function for the given data type and prints the result.

If the user enters an invalid data type:

```cpp
    } else {
        cout << "Invalid data type entered." << endl;
    }
```

If the user enters an invalid data type, the program will print an error message.

End of main() function:

```cpp
    return 0;
}
```

The main() function returns 0 to signal a successful program execution.

By following this study guide, you should gain a better understanding of how overloaded functions work in C++ and how to create a program that handles different data types and operations using the same function name.


## FAQ: Study Guide for double surprise_function(double a, double b)

What does fmod() do in C++?

fmod() is a math library function in C++ that calculates the remainder of the division of two floating-point numbers.

What is the surprise_function doing?

The surprise_function takes two double arguments a and b, and returns the remainder of a divided by b. The function uses the fmod() function to perform this calculation.

What is the function signature of this version of surprise_function?

```cpp
double surprise_function(double a, double b) {
    return fmod(a, b);
}
```

The function takes two double arguments a and b, and returns a double value that is the remainder of a divided by b.

Can you give an example of how this function works?

Suppose we want to calculate the remainder of dividing 10.5 by 3.2. We can call the surprise_function with a = 10.5 and b = 3.2, like this:

```cpp
double result = surprise_function(10.5, 3.2);
```

The fmod() function will calculate the remainder of 10.5 / 3.2, which is approximately 1.9, and return it as a double value. The surprise_function will then return this value to the caller.

How does the concatenation of two characters work in surprise_function?

In the line return string(1, a) + b;, the surprise_function returns a string value that concatenates two char values a and b.

The string(1, a) expression creates a new string object that contains the single character a. The first argument 1 specifies the length of the string, and the second argument a specifies the character to use.

The + operator is then used to concatenate the string containing a with the char value b. Since the + operator is overloaded for string and char, this concatenation works automatically, and the resulting string contains both characters a and b.

So the string(1, a) + b expression is a concise way to concatenate two characters into a string value in C++.

## FAQ Study Guide: What is boolalpha in C++?
Q: What is boolalpha in C++?

boolalpha is a format flag in C++ that is used to control the output formatting of bool values. By default, bool values are output as 0 or 1, which represent false and true, respectively. However, when boolalpha is set, bool values are output as the words "false" and "true", respectively.

Q: How is boolalpha used in C++?

To set the boolalpha format flag, you can use the std::boolalpha manipulator in the output stream. For example, cout << boolalpha << my_bool_var would output true or false depending on the value of my_bool_var.

Q: Where is boolalpha used in the given code example?

In the given code example, boolalpha is used in the else if block that handles the case where the user enters "boolean" as the data type. When this happens, the program prompts the user to enter two bool values, and then sets the boolalpha format flag for the subsequent output. This ensures that the bool values are output as words instead of numbers.

Q: What happens if boolalpha is not set in the given code example?

If boolalpha is not set in the given code example, the bool values entered by the user would be output as 0 or 1, which represent false and true, respectively. Setting boolalpha ensures that the output is more human-readable by using the words "false" and "true" instead.
## Labs

# The Architect - C++ Study Guide


```cpp
#include <iostream>

class BuildingBlueprint {
private:
    int stories;
    int apartments;
    float occupancyRate;
    bool fullyOccupied;

public:
    // Default constructor
    BuildingBlueprint() : stories(10), apartments(20), occupancyRate(1.0), fullyOccupied(true) {}

    // Overloaded (Argument) Constructor
    BuildingBlueprint(int stories, int apartments, float occupancyRate)
        : stories(stories), apartments(apartments), occupancyRate(occupancyRate) {
        fullyOccupied = (occupancyRate == 1.0);
    }

    // Getters
    int getStories() const {
        return stories;
    }

    int getApartments() const {
        return apartments;
    }

    float getOccupancyRate() const {
        return occupancyRate;
    }

    bool isFullyOccupied() const {
        return fullyOccupied;
    }

    // Setters
    void setOccupancyRate(float newOccupancyRate) {
        occupancyRate = newOccupancyRate;
        fullyOccupied = (occupancyRate == 1.0);
    }
};

int main() {
    // Create two building objects
    BuildingBlueprint buildingOne;
    BuildingBlueprint buildingTwo(30, 30, 0.75);

    std::cout << "Year 2020:\n";
    std::cout << "Building 1 has " << buildingOne.getStories() << " floors, " << buildingOne.getApartments() << " apartments, and is " << buildingOne.getOccupancyRate() * 100 << "% occupied. Full? " << (buildingOne.isFullyOccupied() ? "true" : "false") << std::endl;
    std::cout << "Building 2 has " << buildingTwo.getStories() << " floors, " << buildingTwo.getApartments() << " apartments, and is " << buildingTwo.getOccupancyRate() * 100 << "% occupied. Full? " << (buildingTwo.isFullyOccupied() ? "true" : "false") << std::endl;

    std::cout << "Many years pass.\n";

    // Update occupancy rates
    buildingOne.setOccupancyRate(0.0);
    buildingTwo.setOccupancyRate(1.0);

    std::cout << "Year 2043:\n";
    std::cout << "Building 1 has " << buildingOne.getStories() << " floors, " << buildingOne.getApartments() << " apartments, and is " << buildingOne.getOccupancyRate() * 100 << "% occupied. Full? " << (buildingOne.isFullyOccupied() ? "true" : "false") << std::endl;
    std::cout << "Building 2 has " << buildingTwo.getStories() << " floors, " << buildingTwo.getApartments() << " apartments, and is " << buildingTwo.getOccupancyRate() * 100 << "% occupied. Full? " << (buildingTwo.isFullyOccupied() ? "true" : "false") << std::endl;

    std::cout << "Looks like people prefer taller buildings.\n";

    return 0;
}
```


This study guide covers the C++ solution for the Lab13A: The Architect. It explains the code implementation of the BuildingBlueprint class and its usage in the main function.

BuildingBlueprint Class
Attributes

The BuildingBlueprint class has four private attributes:

stories: an integer representing the number of stories the building has.
apartments: an integer representing the number of apartments the building has.
occupancyRate: a float representing the occupancy rate of the building (a number between 0 and 1).
fullyOccupied: a boolean indicating if the building is fully occupied (true if the occupancy rate is 1, otherwise false).
Constructors

The class has two constructors:

Default constructor: Initializes the attributes with default values (10 stories, 20 apartments, 100% occupancy, and fully occupied).
Overloaded (Argument) constructor: Accepts custom values for the number of stories, number of apartments, and occupancy rate. It sets the fullyOccupied attribute based on the provided occupancy rate.
Methods (Behavior)

The class has getters and setters for the following attributes:

Getters and Setters for occupancyRate.
Getters for stories, apartments, and fullyOccupied.
Usage in the main function

Create two BuildingBlueprint objects:

buildingOne using the default constructor.
buildingTwo using the overloaded (argument) constructor with custom values (30 stories, 30 apartments, and 75% occupancy).

Print out the information of buildingOne and buildingTwo using the getters.

Update the occupancy rates of both buildings:

Set the occupancy rate of buildingOne to 0%.
Set the occupancy rate of buildingTwo to 100%.

Print out the updated information of both buildings using the getters.

The output demonstrates the changes in occupancy rates over time and concludes with a remark about people's preference for taller buildings.

Conclusion

This study guide explains the C++ solution for the Lab13A: The Architect problem, including the BuildingBlueprint class and its usage in the main function. Understanding the class design, attributes, constructors, and methods will help you to implement similar classes for other problems.

## Code Explanation

This C++ code defines the `BuildingBlueprint` class and uses it in the `main` function to demonstrate the changes in building occupancy rates over time.

 Include

```cpp
#include <iostream>
```

This line includes the `<iostream>` header file, which provides facilities for input and output streams.

 BuildingBlueprint Class

```cpp
class BuildingBlueprint {
private:
    int stories;
    int apartments;
    float occupancyRate;
    bool fullyOccupied;
```

This section defines the `BuildingBlueprint` class and declares its private attributes:

- `stories`: an integer representing the number of stories the building has.
- `apartments`: an integer representing the number of apartments the building has.
- `occupancyRate`: a float representing the occupancy rate of the building (between 0 and 1).
- `fullyOccupied`: a boolean indicating if the building is fully occupied (true if the occupancy rate is 1, otherwise false).

```cpp
public:
    // Default constructor
    BuildingBlueprint() : stories(10), apartments(20), occupancyRate(1.0), fullyOccupied(true) {}
```

The default constructor initializes the attributes with default values (10 stories, 20 apartments, 100% occupancy, and fully occupied).

```cpp
    // Overloaded (Argument) Constructor
    BuildingBlueprint(int stories, int apartments, float occupancyRate)
        : stories(stories), apartments(apartments), occupancyRate(occupancyRate) {
        fullyOccupied = (occupancyRate == 1.0);
    }
```

The overloaded (argument) constructor accepts custom values for the number of stories, number of apartments, and occupancy rate. It sets the `fullyOccupied` attribute based on the provided occupancy rate.

```cpp
    // Getters
```

This section declares the getter methods for each attribute. These methods return the current value of the respective attribute.

```cpp
    // Setters
```

This section declares the setter method for the `occupancyRate` attribute. The method updates the `occupancyRate` and `fullyOccupied` attributes based on the provided value.

 Main Function

```cpp
int main() {
```

This line defines the entry point of the program, the `main` function.

```cpp
    // Create two building objects
    BuildingBlueprint buildingOne;
    BuildingBlueprint buildingTwo(30, 30, 0.75);
```

This block creates two `BuildingBlueprint` objects:

- `buildingOne`: using the default constructor.
- `buildingTwo`: using the overloaded constructor with custom values (30 stories, 30 apartments, and 75% occupancy).

```cpp
    // Output initial information
```

This block outputs the initial information of both buildings using the getter methods.

```cpp
    // Update occupancy rates
    buildingOne.setOccupancyRate(0.0);
    buildingTwo.setOccupancyRate(1.0);
```

This block updates the occupancy rates of both buildings:

- `buildingOne`: set to 0%.
- `buildingTwo`: set to 100%.

```cpp
    // Output updated information
```

This block outputs the updated information of both buildings using the getter methods.

```cpp
    return 0;
}
```

This line indicates the successful completion of the program by returning 0.

# Color art lab


```cpp
#include <iostream>
#include <string>
using namespace std;

class Pixel {
public:
    int red;
    int green;
    int blue;

    Pixel() : red(255), green(255), blue(255) {}
    Pixel(int r, int g, int b) : red(r), green(g), blue(b) {}

    void changeRGB(int r, int g, int b) {
        red = r;
        green = g;
        blue = b;
    }

    void printRGB() {
        cout << red << " " << green << " " << blue;
    }
};

void initializeArray(Pixel **image, int width, int height, int red, int green, int blue) {
    for (int i = 0; i < height; i++) {
        for (int j = 0; j < width; j++) {
            image[i][j] = Pixel(red, green, blue);
        }
    }
}

void printImage(Pixel **image, int width, int height) {
    cout << "PPM Image Contents" << endl;
    cout << "P3" << endl;
    cout << width << " " << height << endl;
    cout << "255" << endl;
    for (int i = 0; i < height; i++) {
        for (int j = 0; j < width; j++) {
            image[i][j].printRGB();
            cout << " ";
        }
        cout << endl;
    }
}

void fillPixel(Pixel **image, int width, int height) {
    int row, column, red, green, blue;
    cout << "Row: ";
    cin >> row;
    cout << "Column: ";
    cin >> column;
    cout << "New Red Color: ";
    cin >> red;
    cout << "New Green Color: ";
    cin >> green;
    cout << "New Blue Color: ";
    cin >> blue;
    if (row >= 0 && row < height && column >= 0 && column < width && red >= 0 && red <= 255 && green >= 0 && green <= 255 && blue >= 0 && blue <= 255) {
        image[row][column].changeRGB(red, green, blue);
    } else {
        cout << "Invalid information!" << endl;
    }
}

int main() {
    cout << "[Color Art Program]" << endl;
    int width, height, red, green, blue;
    cout << "Enter an image width: ";
    cin >> width;
    cout << "Enter an image height: ";
    cin >> height;
    cout << "Enter the fill color's red value: ";
    cin >> red;
    cout << "Enter the fill color's green value: ";
    cin >> green;
    cout << "Enter the fill color's blue value: ";
    cin >> blue;

    // allocate memory for 2D array
    Pixel **image = new Pixel*[height];
    for (int i = 0; i < height; i++) {
        image[i] = new Pixel[width];
    }

    // initialize array with fill color
    initializeArray(image, width, height, red, green, blue);

    int choice;
    do {
        cout << endl << "What will you do?" << endl;
        cout << "1) Fill in a pixel" << endl;
        cout << "3) Print the image" << endl;
        cout << "4) Quit" << endl;
        cout << "Choice? ";
        cin >> choice;
        switch (choice) {
            case 1:
                fillPixel(image, width, height);
                break;
            case 3:
                printImage(image, width, height);
                break;
            case 4:
                cout << "[Exiting Color Art Program]" << endl;
                break;
            default:
                cout << "Invalid choice!" << endl;
                break;
        }
    } while (choice != 4);

    // free memory for 2D array
    for (int i = 0; i < height; i++) {
        delete[] image[i];
    }
    delete[] image;

    return 0;
}
```

Sure, here's a breakdown of the code component by component:

#include <iostream>
This is a preprocessor directive that allows the use of input and output stream objects, like "cin" and "cout".

#include <string>
This is a preprocessor directive that allows the use of the "string" class.

using namespace std;
This line brings all of the identifiers in the "std" namespace into the current scope, making it unnecessary to prefix them with "std::".

class Pixel { ... };
This declares a class named "Pixel", which has three member variables ("red", "green", and "blue") and three member functions (a default constructor, a parameterized constructor, and two other member functions).

Pixel() : red(255), green(255), blue(255) {}
This is the definition of the default constructor for the "Pixel" class, which initializes the "red", "green", and "blue" member variables to 255.

Pixel(int r, int g, int b) : red(r), green(g), blue(b) {}
This is the definition of a parameterized constructor for the "Pixel" class, which initializes the "red", "green", and "blue" member variables to the values passed as arguments.

void changeRGB(int r, int g, int b) { ... }
This member function changes the values of the "red", "green", and "blue" member variables to the values passed as arguments.

void printRGB() { ... }
This member function prints the values of the "red", "green", and "blue" member variables to the console.

void initializeArray(Pixel **image, int width, int height, int red, int green, int blue) { ... }
This function takes a 2D array of "Pixel" objects, its dimensions, and a fill color, and initializes each element of the array to a "Pixel" object with the specified fill color.

void printImage(Pixel **image, int width, int height) { ... }
This function takes a 2D array of "Pixel" objects and its dimensions, and prints the contents of the array to the console in PPM image format.

void fillPixel(Pixel **image, int width, int height) { ... }
This function prompts the user to input the row and column of a specific "Pixel" object in a 2D array, as well as new values for its "red", "green", and "blue" member variables, and changes those values if the input is valid.

int main() { ... }
This is the main function of the program, which takes user input for the dimensions and fill color of an image, allocates memory for a 2D array of "Pixel" objects, initializes the array with the fill color, and provides a menu for the user to fill in pixels, print the image, or quit the program.

Pixel **image = new Pixel*[height];
This dynamically allocates memory for a 2D array of "Pixel" objects, with dimensions specified by the "height" and "width" variables.

for (int i = 0; i < height; i++) { image[i] = new Pixel[width]; }
This loop initializes each row of the 2D array with a new array of "Pixel" objects, with length specified by the "width" variable.

```cpp                              
red, green, blue);
```
This function call initializes each element of the 2D array with a new "Pixel" object with the fill color specified by the "red", "green", and "blue" variables.

```
 do { ... } while (choice != 4);
```
This loop repeatedly prompts the user to choose an action (fill in a pixel, print the image, or quit the program) until the user chooses to quit.

```
 switch (choice) { ... }
```
This switch statement executes the appropriate action based on the user's choice.

```
for (int i = 0; i < height; i++) { delete[] image[i]; }
```
This loop deallocates memory for each row of the 2D array.

```
 delete[] image;
```
This deallocates memory for the 2D array itself.

```
 return 0;
```
This indicates that the program has executed successfully and returns control to the operating system.

# Ro-Sham-Bo Game: A C++ Study Guide

```cpp
#include <iostream>
#include <string>
#include <ctime>
#include <cstdlib>

class RoshamboPlayer {
private:
    std::string playerName;
    std::string attack;
    int roLimit;
    int shamBoLimit;

public:
    RoshamboPlayer(const std::string& name, int roLimit, int shamBoLimit)
        : playerName(name), roLimit(roLimit), shamBoLimit(shamBoLimit) {
        srand(time(0));
    }

    bool playRound(const std::string& playerAttack) {
        int randomValue = rand() % 101;
        if (randomValue < roLimit) {
            attack = "Ro";
        } else if (randomValue < shamBoLimit) {
            attack = "Sham";
        } else {
            attack = "Bo";
        }

        if (playerAttack == attack) {
            return false;
        } else if ((playerAttack == "Ro" && attack == "Sham") || (playerAttack == "Sham" && attack == "Bo") || (playerAttack == "Bo" && attack == "Ro")) {
            return false;
        } else {
            return true;
        }
    }

    std::string getName() const {
        return playerName;
    }

    std::string getAttack() const {
        return attack;
    }
};

int main() {
    RoshamboPlayer p1("R. Dorothy", 30, 60);
    RoshamboPlayer p2("Johnny 5", 40, 85);
    RoshamboPlayer* chosenPlayer;
    std::string input;
    int choice;

    std::cout << "[Ro-Sham-Bo Player]\n";
    std::cout << "Who do you want to face?\n";
    std::cout << "1) " << p1.getName() << std::endl;
    std::cout << "2) " << p2.getName() << std::endl;
    std::cout << "Opponent: ";
    std::cin >> choice;

    if (choice == 1) {
        chosenPlayer = &p1;
    } else {
        chosenPlayer = &p2;
    }

    std::cout << "Your opponent is " << chosenPlayer->getName() << "!" << std::endl;

    while (true) {
        std::cout << "1) Play a round?\n";
        std::cout << "2) Quit?\n";
        std::cout << "Choice: ";
        std::cin >> choice;

        if (choice == 2) {
            std::cout << "Game Over" << std::endl;
            break;
        }

        while (true) {
            std::cout << "Enter an attack: ";
            std::cin >> input;
            if (input == "Ro" || input == "Sham" || input == "Bo") {
                break;
            }
            std::cout << "Invalid attack!" << std::endl;
        }

        if (chosenPlayer->playRound(input)) {
            std::cout << chosenPlayer->getName() << " chose " << chosenPlayer->getAttack() << "! You win!" << std::endl;
        } else {
            std::cout << chosenPlayer->getName() << " chose " << chosenPlayer->getAttack() << "! You lose..." << std::endl;
        }
    }

    return 0;
}
```


This study guide will help you understand the C++ implementation of the Ro-Sham-Bo game.

## Included Libraries

```cpp
#include <iostream>
#include <string>
#include <ctime>
#include <cstdlib>
```

These libraries are included for input/output operations, string manipulation, and random number generation.

## RoshamboPlayer Class

```cpp
class RoshamboPlayer {
private:
    std::string playerName;
    std::string attack;
    int roLimit;
    int shamBoLimit;
```

The `RoshamboPlayer` class contains four private attributes: playerName, attack, roLimit, and shamBoLimit.

### Constructor

```cpp
public:
    RoshamboPlayer(const std::string& name, int roLimit, int shamBoLimit)
        : playerName(name), roLimit(roLimit), shamBoLimit(shamBoLimit) {
        srand(time(0));
    }
```

The constructor initializes the playerName, roLimit, and shamBoLimit attributes, and seeds the random number generator.

### playRound Method

```cpp
bool playRound(const std::string& playerAttack) {
    int randomValue = rand() % 101;
    if (randomValue < roLimit) {
        attack = "Ro";
    } else if (randomValue < shamBoLimit) {
        attack = "Sham";
    } else {
        attack = "Bo";
    }

    if (playerAttack == attack) {
        return false;
    } else if ((playerAttack == "Ro" && attack == "Sham") || (playerAttack == "Sham" && attack == "Bo") || (playerAttack == "Bo" && attack == "Ro")) {
        return false;
    } else {
        return true;
    }
}
```

The `playRound` method takes the player's attack as an input, generates the computer's attack based on roLimit and shamBoLimit, and returns `true` if the player wins or `false` if the computer wins or the game is a draw.

### getName and getAttack Methods

```cpp
std::string getName() const {
    return playerName;
}

std::string getAttack() const {
    return attack;
}
```

These two methods are simple getters for the playerName and attack attributes.

## Main Function

```cpp
int main() {
```

The main function handles user input and game logic.

### Create Players

```cpp
RoshamboPlayer p1("R. Dorothy", 30, 60);
RoshamboPlayer p2("Johnny 5", 40, 85);
RoshamboPlayer* chosenPlayer;
```

Two `RoshamboPlayer` objects are created, and a pointer to the chosen player is declared.

### Choose Opponent

```cpp
std::cout << "[Ro-Sham-Bo Player]\n";
// ... (omitted for brevity) ...
std::cin >> choice;

if (choice == 1) {
    chosenPlayer = &p1;
} else {
    chosenPlayer = &p2;
}
```

The user is prompted to choose an opponent, and the chosenPlayer pointer is set accordingly.

### Game Loop

```cpp
while (true) {
    // ... (omitted for brevity) ...

    if (choice == 2) {
        std::cout << "Game Over" << std::endl;
        break;
    }

    // ... (omitted for brevity) ...

    if (chosenPlayer->playRound(input)) {
        std::cout << chosenPlayer->getName() << " chose " << chosenPlayer->getAttack() << "! You win!" << std::endl;
    } else {
        std::cout << chosenPlayer->getName() << " chose " << chosenPlayer->getAttack() << "! You lose..." << std::endl;
    }
}
```

The game loop continues until the user chooses to quit. Inside the loop, the user is prompted to play a round or quit. If the user chooses to play a round, they are prompted to enter an attack ("Ro", "Sham", or "Bo"). If the user's input is invalid, they are prompted again until they provide valid input.

Once the user has entered a valid attack, the `playRound` method of the `chosenPlayer` object is called with the user's input. The method's return value determines whether the player has won or lost. The loop then repeats, prompting the user to play another round or quit.

The game loop ends when the user chooses to quit, and the program displays "Game Over".

```cpp
return 0;
}
```

The main function returns 0 to indicate successful execution.

This study guide covers the key concepts and code implementation of the Ro-Sham-Bo game in C++. By understanding the different components of the program, you can gain a deeper understanding of C++ programming, object-oriented programming, and game development.


Below is a component-by-component explanation of the code:

1. **Header files**: The code includes four header files:

```cpp
   #include <iostream>
   #include <string>
   #include <ctime>
   #include <cstdlib>
```

   `iostream` enables input and output operations, `string` is for string manipulation, `ctime` provides time functions, and `cstdlib` contains functions for random number generation.

2. **Class declaration: RoshamboPlayer**: The class `RoshamboPlayer` is declared, containing private data members and public member functions.

```cpp
   class RoshamboPlayer {
   private:
       std::string playerName;
       std::string attack;
       int roLimit;
       int shamBoLimit;
```

   `playerName`, `attack`, `roLimit`, and `shamBoLimit` are private data members, which store the player's name, current attack, and limits for determining the random attack.

3. **Constructor**: The constructor initializes the `RoshamboPlayer` object with a name, `roLimit`, and `shamBoLimit` values. It also seeds the random number generator with the current time.

```cpp
   public:
       RoshamboPlayer(const std::string& name, int roLimit, int shamBoLimit)
           : playerName(name), roLimit(roLimit), shamBoLimit(shamBoLimit) {
           srand(time(0));
       }
```

4. **playRound function**: This function generates a random attack for the computer player and compares it to the player's attack to determine if the player has won or lost the round.

```cpp
       bool playRound(const std::string& playerAttack) {
           int randomValue = rand() % 101;
           if (randomValue < roLimit) {
               attack = "Ro";
           } else if (randomValue < shamBoLimit) {
               attack = "Sham";
           } else {
               attack = "Bo";
           }

           if (playerAttack == attack) {
               return false;
           } else if ((playerAttack == "Ro" && attack == "Sham") || (playerAttack == "Sham" && attack == "Bo") || (playerAttack == "Bo" && attack == "Ro")) {
               return false;
           } else {
               return true;
           }
       }
```

5. **getName and getAttack functions**: These functions return the player's name and current attack, respectively.

```cpp
       std::string getName() const {
           return playerName;
       }

       std::string getAttack() const {
           return attack;
       }
   };

```

6. **main function**: The main function creates two `RoshamboPlayer` objects, `p1` and `p2`, with different attributes. It also declares variables for user input and game choices.

```cpp
   int main() {
       RoshamboPlayer p1("R. Dorothy", 30, 60);
       RoshamboPlayer p2("Johnny 5", 40, 85);
       RoshamboPlayer* chosenPlayer;
       std::string input;
       int choice;
```

7. **User opponent selection**: The program prompts the user to choose an opponent and stores the selected opponent in the `chosenPlayer` pointer.

```cpp
       std::cout << "[Ro-Sham-Bo Player]\n";
       std::cout << "Who do you want to face?\n";
       std::cout << "1) " << p1.getName() << std::endl;
       std::cout << "2) " << p2.getName() << std::endl;
   std::cout << "Opponent: ";
   std::cin >> choice;

   if (choice == 1) {
       chosenPlayer = &p1;
   } else {
       chosenPlayer = &p2;
   }

   std::cout << "Your opponent is " << chosenPlayer->getName() << "!" << std::endl;
```

8. **Game loop**: The program enters a loop where it prompts the user to either play a round or quit the game. If the user chooses to play, they are prompted to enter a valid attack.

```cpp
   while (true) {
       std::cout << "1) Play a round?\n";
       std::cout << "2) Quit?\n";
       std::cout << "Choice: ";
       std::cin >> choice;

       if (choice == 2) {
           std::cout << "Game Over" << std::endl;
           break;
       }

       while (true) {
           std::cout << "Enter an attack: ";
           std::cin >> input;
           if (input == "Ro" || input == "Sham" || input == "Bo") {
               break;
           }
           std::cout << "Invalid attack!" << std::endl;
       }
```

9. **Round result**: The program calls the `playRound` function with the user's input and displays the result of the round based on the function's return value.

```cpp
       if (chosenPlayer->playRound(input)) {
           std::cout << chosenPlayer->getName() << " chose " << chosenPlayer->getAttack() << "! You win!" << std::endl;
       } else {
           std::cout << chosenPlayer->getName() << " chose " << chosenPlayer->getAttack() << "! You lose..." << std::endl;
       }
   }

   return 0;
}
```

The program will keep looping through the game until the user chooses to quit.
        


# Final exam 


```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
    int x;
    int v;
    string s;
    int V1 = 13;
    string S1 = "Spades";
    int V2 = 11;
    string S2 = "Hearts";

    cout << "[Famous Card Hands]" << endl;
    cout << "1) Dead Man's Hand" << endl;
    cout << "2) Maverick Hand" << endl;
    cout << "Card: ";
    cin >> x;

    switch (x) {
        case 1:
            cout << "We have Ace of Clubs, 8 of Spades, and 8 of Clubs. Which card is missing?" << endl;
            cout << "Value: ";
            cin >> v;
            cout << "Suite: ";
            cin >> s;

            if (v < 10) {
                cout << "You guessed " << v << " of " << s << "." << endl;
            }
            if (v == 10) {
                cout << "You guessed Jack of " << s << "." << endl;
            }
            if (v == 11) {
                cout << "You guessed Queen of " << s << "." << endl;
            }
            if (v == 12) {
                cout << "You guessed King of " << s << "." << endl;
            }
            if (v == 13) {
                cout << "You guessed Ace of " << s << "." << endl;
            }

            if (v == V1 && s == S1) {
                cout << "Correct!";
            } else {
                cout << "Incorrect...";
            }
            break;

        case 2:
            cout << "We have Queen of Spades, Jack of Hearts, Jack of Spades, and Jack of Clubs. Which card is missing?" << endl;
            cout << "Value: ";
            cin >> v;
            cout << "Suite: ";
            cin >> s;

            if (v < 10) {
                cout << "You guessed " << v << " of " << s << "." << endl;
            }
            if (v == 10) {
                cout << "You guessed Jack of " << s << "." << endl;
            }
            if (v == 11) {
                cout << "You guessed Queen of " << s << "." << endl;
            }
            if (v == 12) {
                cout << "You guessed King of " << s << "." << endl;
            }
            if (v == 13) {
                cout << "You guessed Ace of " << s << "." << endl;
            }

            if (v == V2 && s == S2) {
                cout << "Correct!";
            } else {
                cout << "Incorrect...";
            }
            break;
    }
    return 0;
}
```
    
This code is a simple C++ program that simulates a card guessing game based on two famous card hands: "Dead Man's Hand" and "Maverick Hand". The user has to guess the missing card in each hand, and the program provides feedback on whether the guess is correct or incorrect.

Here's a component-by-component breakdown of the code:

1. Header includes and namespace declaration:


```cpp
#include <iostream>
#include <string>
using namespace std;
```
The code imports the `iostream` and `string` libraries, and declares the use of the `std` namespace.

2. Main function:


```cpp
int main() {
```
The main function is where the program execution starts.

3. Variable declarations:


```cpp
int x;
int v;
string s;
int V1 = 13;
string S1 = "Spades";
int V2 = 11;
string S2 = "Hearts";
```
Variables are declared and initialized with values for the correct missing cards.

4. Introduction and input:


```cpp
cout << "[Famous Card Hands]" << endl;
cout << "1) Dead Man's Hand" << endl;
cout << "2) Maverick Hand" << endl;
cout << "Card: ";
cin >> x;
```
The program introduces the two card hands and prompts the user to select one.

5. Switch statement:


```cpp
switch (x) {
```
A switch statement is used to handle the two cases based on the user's input.

6. Case 1: Dead Man's Hand


```cpp
case 1:
    ...
    break;
```
In this case, the program describes the Dead Man's Hand, prompts the user for their guess, and provides feedback on whether the guess is correct or incorrect.

7. Case 2: Maverick Hand


```cpp
case 2:
    ...
    break;
```
In this case, the program describes the Maverick Hand, prompts the user for their guess, and provides feedback on whether the guess is correct or incorrect.

8. End of the switch statement and main function:


```cpp
}
return 0;
}
```
The switch statement and the main function are closed. The program returns 0 to indicate successful execution.    
    
    
# Multi-Converter study guide

```cpp
#include <iostream>
using namespace std;

int main() {
    float F;
    cout << "Multi-Converter" << endl;
    cout << "Enter a value in Fahrenheit: ";
    cin >> F;
    cout << endl;

    float K = (F - 32) * 5 / 9 + 273.15;
    int k = static_cast<int>(K);

    cout << F << "F is approximately " << K << " in Kelvin." << endl;
    cout << "If we cast it to an int, it becomes " << k << "K." << endl;
    cout << endl;

    int X;
    cout << "What would you like to change this by? ";
    cin >> X;
    cout << endl;

    int newK = k + X;
    float newF = (newK - 273.15) * 9 / 5 + 32;

    cout << "We now have " << newK << "K." << endl;
    cout << newK << "K is approximately " << newF << "F in Fahrenheit." << endl;
}
```

Here's a breakdown of each component in the code:

1. `#include <iostream>`: This line is a preprocessor directive that includes the iostream header file, which is required for input/output (I/O) operations using C++ streams.

2. `using namespace std;`: This line tells the compiler to use the standard namespace (std), which provides access to standard functions and objects such as cout and cin without having to use the prefix "std::".

3. `int main() { ... }`: The main function is the entry point of the C++ program. It is where the program starts executing.

4. Variable declarations:
   - `float F;`: This variable stores the user input for the temperature in Fahrenheit.
   - `float K;`: This variable stores the calculated temperature in Kelvin.
   - `int k;`: This variable stores the integer value of the temperature in Kelvin.
   - `int X;`: This variable stores the user input for the value to change the temperature.
   - `int newK;`: This variable stores the updated temperature in Kelvin.
   - `float newF;`: This variable stores the updated temperature in Fahrenheit.

5. `cin >> F;`: This line reads the user input for the temperature in Fahrenheit and stores it in the variable F.

6. `float K = (F - 32) * 5 / 9 + 273.15;`: This line calculates the temperature in Kelvin using the formula to convert Fahrenheit to Kelvin and stores it in the variable K.

7. `int k = static_cast<int>(K);`: This line safely casts the float value of K to an integer and stores it in the variable k.

8. The following `cout` statements print the input temperature in Fahrenheit, the calculated temperature in Kelvin, and the integer value of the temperature in Kelvin.

9. `cin >> X;`: This line reads the user input for the value to change the temperature and stores it in the variable X.

10. `int newK = k + X;`: This line calculates the updated temperature in Kelvin by adding the user input X to the integer value k and stores it in the variable newK.

11. `float newF = (newK - 273.15) * 9 / 5 + 32;`: This line calculates the updated temperature in Fahrenheit using the formula to convert Kelvin to Fahrenheit and stores it in the variable newF.

12. The following `cout` statements print the updated temperature in Kelvin and the updated temperature in Fahrenheit.

This code takes a temperature in Fahrenheit as input, converts it to Kelvin, and then adjusts the temperature by an integer value provided by the user before converting it back to Fahrenheit and displaying the results.


# Vending Machine study guide

```cpp
#include <iostream>
using namespace std;

int main() {
    float x;
    float change;
    char y;
    char Z;

    cout << "[Vending Machine Simulation]" << endl;
    cout << "Put your money in the machine: ";
    cin >> x;
    cout << endl;

    do {
        cout << "Here's what you can buy:" << endl;
        cout << "A) Bag of Computer Chips ($2)" << endl;
        cout << "B) Infinite Loop Bar ($1.50)" << endl;
        cout << "Selection: ";
        cin >> y;
        
        if (y == 'A') {
            float price = 2;
            if (x >= price) {
                cout << "Okay, you bought a Bag of Computer Chips!" << endl;
                change = x - price;
                x = change;
            } else {
                cout << "Sorry, you only have $" << x << " left." << endl;
            }
        } else if (y == 'B') {
            float price = 1.50;
            if (x >= price) {
                cout << "Okay, you bought an Infinite Loop Bar!" << endl;
                change = x - price;
                x = change;
            } else {
                cout << "Sorry, you only have $" << x << " left." << endl;
            }
        } else {
            cout << "Invalid selection." << endl;
        }

        cout << endl;
        cout << "Do you want to buy anything else? (Y/N): ";
        cin >> Z;
    } while (Z == 'Y' || Z == 'y');

    cout << "Ending the Vending Machine simulation." << endl;
}

```
Here's a breakdown of each component in the code:

1. `#include <iostream>`: This line is a preprocessor directive that includes the iostream header file, which is required for input/output (I/O) operations using C++ streams.

2. `using namespace std;`: This line tells the compiler to use the standard namespace (std), which provides access to standard functions and objects such as cout and cin without having to use the prefix "std::".

3. `int main() { ... }`: The main function is the entry point of the C++ program. It is where the program starts executing.

4. Variable declarations:
   - `float x;`: This variable stores the amount of money the user inputs.
   - `float change;`: This variable stores the change after a purchase.
   - `char y;`: This variable stores the user's selection of the product.
   - `char Z;`: This variable stores the user's decision on whether to buy anything else.

5. `cout << "[Vending Machine Simulation]" << endl;`: This line prints the title of the simulation and moves to the next line using "endl".

6. `cin >> x;`: This line reads the user input for the amount of money and stores it in the variable x.

7. The `do { ... } while (Z == 'Y' || Z == 'y');` loop repeats the vending machine simulation until the user decides not to buy anything else (when Z is not 'Y' or 'y').

8. Inside the loop, the program presents the available products and asks the user to choose one.

9. The `if (y == 'A') { ... } else if (y == 'B') { ... } else { ... }` block checks the user's selection and processes the purchase accordingly.

10. After the purchase or an invalid selection, the program asks the user if they want to buy anything else and stores the response in the variable Z.

11. Finally, when the user decides not to buy anything else, the program prints "Ending the Vending Machine simulation." and exits the main function, terminating the program.

# Question Bank
# Data Types and Input/Output Practice Problems in C++

## True/False Questions

1. `count--` is equivalent to `count = count + 1`.
2. `count++` is equivalent to `count = count + 1`.
3. Keywords can be used as variable identifiers/names.
4. Escape sequences are used to print special characters such as `\` and `“`.
5. Constants are used to make program maintenance easier.
6. Abstraction refers to the logical grouping of concepts or objects.
7. Literals are values that are entered directly into code.
8. Logical operators are evaluated before relational operators.
9. Strings are a primitive data type.
10. Brute force is a good approach to programming.
11. You must declare and initialize a variable in two separate steps.
12. When assigning a value to a variable, the variable must be on the left of the assignment operator (`=`).
13. The escape sequence character (`\`) is used to print special characters in an output string.
14. Logical operators are evaluated before relational operators.

## Answers and Explanations

1. **False**. The `count--` operation is equivalent to `count = count - 1`, which means it decrements the value of `count` by 1.

2. **True**. The `count++` operation is equivalent to `count = count + 1`, which means it increments the value of `count` by 1.

3. **False**. Keywords are reserved words in C++ and cannot be used as variable identifiers/names.

4. **True**. Escape sequences are used to represent special characters in strings. For example, `\\` represents a backslash, and `\"` represents a double quote.

5. **True**. Constants are fixed values that do not change during the execution of a program. They make program maintenance easier by allowing changes to be made in one place.

6. **True**. Abstraction is a programming concept that involves grouping related concepts or objects together to simplify complex systems.

7. **True**. Literals are values that are directly entered into code, such as `5`, `'a'`, or `"Hello"`.

8. **False**. Relational operators are evaluated before logical operators in C++.

9. **False**. In C++, strings are not a primitive data type. They are represented using the `std::string` class from the C++ Standard Library.

10. **False**. Brute force is not always a good approach to programming. It may work for simple problems, but it is often inefficient for complex problems.

11. **False**. You can declare and initialize a variable in the same step. For example: `int count = 5;`.

12. **True**. When assigning a value to a variable, the variable must be on the left side of the assignment operator (`=`). For example: `count = 10;`.

13. **True**. The escape sequence character (`\`) is used to represent special characters in strings. For example, `\\` represents a backslash, and `\"` represents a double quote.

14. **False**. Relational operators are evaluated before logical operators in C++.

# Multiple Choice Questions and Answers

## Question 1
**Which of these is not a property of a good algorithm?**
A) Unambiguous
B) Complete
C) Precise
D) Complex

### Answer
D) Complex

### Explanation
A good algorithm should be unambiguous, complete, and precise. It should have clear and well-defined steps, and it should produce the correct output for any valid input. A complex algorithm is not necessarily a good algorithm, as complexity can make it difficult to understand and maintain. Simplicity and clarity are desirable properties of a good algorithm.

## Question 2
**What is the shortcut operator to add one (1) to a variable?**
A) ++
B) + +
C) **
D) @@

### Answer
A) ++

### Explanation
The `++` operator is known as the increment operator in C++ and other programming languages. It is used to increase the value of a variable by one (1). For example, if we have a variable `count` with the value `5`, using `count++` will increase its value to `6`.

## List of Primitive Data Types and Their Range of Values

1) `bool`: Represents a boolean value, which can be either `true` or `false`.

2) `char`: Represents a single character. The range of values is typically from `-128` to `127` or from `0` to `255`, depending on the implementation.

3) `unsigned char`: Represents an unsigned character. The range of values is from `0` to `255`.

4) `short`: Represents a short integer. The range of values is typically from `-32,768` to `32,767`.

5) `unsigned short`: Represents an unsigned short integer. The range of values is from `0` to `65,535`.

6) `int`: Represents an integer. The range of values is typically from `-2,147,483,648` to `2,147,483,647`.

7) `unsigned int`: Represents an unsigned integer. The range of values is from `0` to `4,294,967,295`.

8) `float`: Represents a single-precision floating-point number. The range of values depends on the implementation, but it typically includes values from approximately `1.2E-38` to `3.4E+38`.

Note: The exact range of values for integer data types (`char`, `short`, `int`, etc.) may vary depending on the implementation and the architecture of the system. The ranges provided here are based on typical implementations using a 32-bit `int` and 8-bit `char`.

# Arrays, Searching & Sorting Practice Problems

## True/False Questions

1. A single array can hold multiple values of different data types.
2. Array Lists can have more than one (1) dimension.
3. A Linear Search is always more efficient than a Binary Search.
4. Arrays must be sorted for a Binary Search to work correctly.

## Answers and Explanations

1. **False**. A single array can hold multiple values, but all values must be of the same data type. For example, an array of integers can hold multiple integer values, but it cannot hold values of different data types such as floating-point numbers or characters.

2. **False**. The term "Array List" typically refers to a dynamic array or a resizable array, which is a one-dimensional data structure. While multi-dimensional arrays do exist, Array Lists themselves are one-dimensional. If multi-dimensional behavior is needed, one can use an Array List of Array Lists or similar constructs.

3. **False**. A Linear Search has a time complexity of O(n), where n is the number of elements in the array. It involves searching each element of the array one by one until the desired element is found. On the other hand, a Binary Search has a time complexity of O(log n) and is more efficient for large arrays. Binary Search works by repeatedly dividing the sorted array into halves and narrowing down the search interval until the desired element is found.

4. **True**. Arrays must be sorted for a Binary Search to work correctly. Binary Search relies on the fact that the array is sorted to efficiently narrow down the search interval. If the array is not sorted, the Binary Search algorithm may produce incorrect results or fail to find the desired element.

# Multiple Choice Questions and Answers

## Question 1
**Arrays are homogeneous, which means:**
a. They can only contain one type of data.
b. They can contain multiple types of data.
c. They are static in size.
d. The index starts at 1.

### Answer
a. They can only contain one type of data.

### Explanation
Arrays are homogeneous data structures, which means they can only contain elements of the same data type. For example, an integer array can only contain integers, and a string array can only contain strings. This is one of the fundamental characteristics of arrays in many programming languages.

## Question 2
**To traverse multidimensional arrays, you most commonly use _____ loops:**
a. NOT
b. pointer
c. infinite
d. nested

### Answer
d. nested

### Explanation
Nested loops are most commonly used to traverse multidimensional arrays. A multidimensional array is essentially an array of arrays, so to access each element, you need one loop for each dimension. For example, to traverse a 2D array, you would use a nested loop: the outer loop iterates over the rows, and the inner loop iterates over the columns.

## Question 3
**Which of these sorts was NOT covered in the CSE 1321 slides:**
a. Bubble
b. Insertion
c. Selection
d. Merge

### Answer
d. Merge

### Explanation
This question is specific to the content covered in a particular course (CSE 1321) and may not apply universally. As of my knowledge cutoff in September 2021, I don't have access to the specific slides for CSE 1321. However, in general computer science curricula, Bubble, Insertion, and Selection sorts are often covered before Merge sort, as they are simpler and more straightforward, although less efficient.

## Question 4
**1D & 2D arrays are:**
a. Used to store multiple types of data
b. Used to prevent data overflow errors
c. Used to store multiple values of the same data type
d. Used to confuse students

### Answer
c. Used to store multiple values of the same data type

### Explanation
1D and 2D arrays are used to store multiple values of the same data type. As mentioned earlier, arrays are homogeneous data structures, which means they can only contain elements of the same data type. A 1D array is a linear array with a single row of elements, while a 2D array is an array of arrays, often thought of as a table with rows and columns.
# Selection Structure Practice Problems

## True/False Questions

1. In an IF…ELSE IF…ELSE IF structure, each statement whose expressions evaluate to true will run their block of code.
2. In an IF…ELSE IF…ELSE IF statement, the first conditional expression that evaluates to true is the only block of code that will run.
3. In an IF…ELSEIF…ELSEIF statement, the first conditional expression that evaluates to true is the only block of code that will run.
4. In a program statement, both the IF and ELSE statements will be executed every time.
5. A DEFAULT CASE is required as part of a SWITCH statement.

## Answers and Explanations

1. **False**. In an IF…ELSE IF…ELSE IF structure, only the block of code corresponding to the first conditional expression that evaluates to true will be executed. Once a true condition is found and its block of code is executed, the program will exit the entire IF…ELSE IF…ELSE IF structure and will not evaluate any further conditions.

2. **True**. In an IF…ELSE IF…ELSE IF statement, the first conditional expression that evaluates to true is the only block of code that will run. Once a true condition is found, the program will execute the corresponding block of code and then exit the entire IF…ELSE IF…ELSE IF structure.

3. **True**. In an IF…ELSEIF…ELSEIF statement (which is equivalent to IF…ELSE IF…ELSE IF), the first conditional expression that evaluates to true is the only block of code that will run. The program will execute the corresponding block of code and then exit the entire IF…ELSEIF…ELSEIF structure.

4. **False**. In a program statement, only one of the IF and ELSE statements will be executed, not both. If the condition in the IF statement evaluates to true, the block of code inside the IF statement will be executed. If the condition evaluates to false, the block of code inside the ELSE statement (if present) will be executed.

5. **False**. A DEFAULT CASE is not required as part of a SWITCH statement. The DEFAULT CASE is optional and is used to specify a block of code that will be executed if none of the CASE values match the expression in the SWITCH statement. If a DEFAULT CASE is not provided and no CASE values match, the SWITCH statement will simply do nothing and the program will continue executing the code after the SWITCH statement.

   
# Multiple Choice Questions and Answers

## Question 1
**Selection structures use what type of expression to determine if a block of code should run.**
a. Boolean
b. Byte
c. Bitlocker
d. Bubble

### Answer
a. Boolean

### Explanation
Selection structures, such as `if`, `if-else`, and `switch` statements, use Boolean expressions to determine if a block of code should run. A Boolean expression is a logical statement that can be either `true` or `false`. For example, in an `if` statement, the code within the `if` block will run if the Boolean expression evaluates to `true`.

## Question 2
**What is the name of the CASE that executes if no other cases match for a SWITCH selection structure?**
a. Default
b. Else
c. InCase
d. None

### Answer
a. Default

### Explanation
In a `switch` selection structure, the `default` case is executed if no other cases match. The `default` case is optional and can be used to handle unexpected or default conditions. If no `default` case is provided and no other cases match, the `switch` statement will simply do nothing and the program will continue executing the code after the `switch` statement.
   
   
# Repetition Structure Practice Problems

## True/False Questions

1. Only WHILE loops can be nested.
2. Only FOR loops can be nested.
3. The main difference between a DO…WHILE and a WHILE loop is that a WHILE loop cannot result in an infinite loop.

## Answers and Explanations

1. **False**. Any type of loop, including WHILE loops, FOR loops, and DO…WHILE loops, can be nested within another loop. Nesting loops means placing one loop inside the body of another loop. This is commonly used for tasks such as iterating over multi-dimensional arrays or performing repeated operations within a loop.

2. **False**. Similar to the explanation for question 1, any type of loop can be nested, not just FOR loops. FOR loops, WHILE loops, and DO…WHILE loops can all be nested within each other or within themselves.

3. **False**. The main difference between a DO…WHILE loop and a WHILE loop is that a DO…WHILE loop is guaranteed to execute its loop body at least once, regardless of whether the loop condition is true or false. This is because the loop condition is checked after the loop body is executed. In contrast, a WHILE loop checks the loop condition before executing the loop body, so it may not execute the loop body at all if the condition is false from the start. Both DO…WHILE and WHILE loops can result in infinite loops if the loop condition remains true indefinitely.

# Multiple Choice Questions and Answers

## Question 1
**This special input value is used to allow a user to end a loop:**
a. Stationary
b. Sentinel
c. Stop
d. Iteration

### Answer
b. Sentinel

### Explanation
A sentinel value is a special input value that is used to signal the end of a loop. It is also known as a flag value or a loop control value. When the program reads the sentinel value, it knows that it should terminate the loop and proceed to the next part of the program.

## Question 2
**The execution of one pass of a loop is referred to as a(n):**
a. Iteration
b. Increment
c. Initialization
d. Individual

### Answer
a. Iteration

### Explanation
An iteration refers to the execution of one pass of a loop. Each time the loop body is executed, it is considered one iteration of the loop.

## Question 3
**Repetition structures use what type of expression to determine if the block of code should run.**
a. Boolean
b. Byte
c. Bitlocker
d. Bubble

### Answer
a. Boolean

### Explanation
Repetition structures, such as loops, use Boolean expressions to determine if the block of code should run. A Boolean expression evaluates to either true or false. If the expression is true, the loop body will be executed; otherwise, the loop will terminate.

## Question 4
**Which of these is not a type of loop?**
a. FOR
b. DO…WHILE
c. WHILE…DO
d. WHILE

### Answer
c. WHILE…DO

### Explanation
The common types of loops in programming languages are the FOR loop, the DO…WHILE loop, and the WHILE loop. There is no standard loop type called WHILE…DO.

## Question 5
**This statement ends a loop immediately:**
a. HALT
b. CONTINUE
c. ESCAPE
d. BREAK

### Answer
d. BREAK

### Explanation
The BREAK statement is used to exit a loop immediately. When the BREAK statement is encountered, the program will exit the current loop and continue executing the code after the loop.

## Question 6
**This statement skips an iteration of a loop:**
a. NEXT
b. CONTINUE
c. SKIP
d. BREAK

### Answer
b. CONTINUE

### Explanation
The CONTINUE statement is used to skip the current iteration of a loop and move on to the next iteration. When the CONTINUE statement is encountered, the program will skip the remaining code in the loop body and proceed to the next iteration.

## Question 7
**FOR Loops are often called what type of loop?**
a. Counting
b. Correcting
c. Incrementing
d. Infinite

### Answer
a. Counting

### Explanation
FOR loops are often called counting loops because they are commonly used to iterate a specific number of times based on a counter variable. The counter variable is initialized, incremented (or decremented), and checked against a condition in each iteration of the loop.


# OOP (Classes & Objects) Practice Problems

## True/False Questions

1. Encapsulation is enforced by setting class attributes to private.
2. Coding a class creates a new simple data type.
3. Methods should be marked private and attributes should be marked public.
4. Constructors do not have a return type declared in the header.

## Answers and Explanations

1. **True**. Encapsulation is a fundamental concept in object-oriented programming (OOP) that refers to the bundling of data (attributes) and methods (functions) within a class while restricting access to certain components. Encapsulation is enforced by setting class attributes to private (or protected) and providing public methods (getters and setters) to access and modify these attributes. This ensures that the internal state of the object is protected from unauthorized access and modification.

2. **False**. Coding a class does not create a new simple data type; rather, it creates a new complex or composite data type known as a class or user-defined type. Simple data types (also known as primitive data types) include basic types such as integers, floating-point numbers, characters, and booleans. In contrast, classes allow programmers to define custom data types that can contain multiple attributes and methods, making them more complex and versatile.

3. **False**. In general, class attributes should be marked private (or protected) to enforce encapsulation, and methods should be marked public to allow external access to the object's behavior. By marking attributes as private, we prevent direct access to the object's internal state from outside the class. Public methods, including getters and setters, provide controlled access to the object's attributes and allow the object to perform specific actions.

4. **True**. Constructors are special methods in a class that are used to initialize objects of that class. Constructors do not have a return type declared in the header, and their name is the same as the class name. Constructors can have parameters to initialize the attributes of the object, but they do not return any value. In some programming languages (such as C++), if no constructor is explicitly defined, the compiler provides a default constructor with no parameters.



## Multiple Choice Questions and Answers

Question 1
**An object’s state refers to:**
a. Its set of methods
b. Its set of data fields with the current values
c. Its skeleton
d. Its constructor’s parameters

### Answer
b. Its set of data fields with the current values

### Explanation
An object's state refers to the values of its data fields (also known as attributes or properties) at a given point in time. The state represents the current condition or characteristics of the object. For example, if we have a class `Car` with attributes `color` and `speed`, the state of a `Car` object could be represented by the current values of these attributes, such as `color = "red"` and `speed = 60`.

## Question 2
**Class variables are also called:**
a. Accessors
b. Constructors
c. Attributes
d. Behavior

### Answer
c. Attributes

### Explanation
Class variables, also known as attributes, properties, or data members, are variables that are defined within a class and are used to represent the characteristics or state of an object. Attributes store the data associated with each instance of the class. For example, in a class `Person`, the attributes could be `name`, `age`, and `gender`.

## Question 3
**Applying which term to a method allows the method to be called without creating an instance of the class it is in:**
a. Static
b. Public
c. Private
d. Scope

### Answer
a. Static

### Explanation
The term "static" is applied to a method to make it a static method. A static method belongs to the class itself rather than to any instance of the class. As a result, it can be called without creating an instance of the class. Static methods are often used for utility functions that do not depend on the state of an object.

## Question 4
**Creating multiple methods (or constructors) with the same name but different parameters (number of parameters and/or data type of parameters and/or order of parameters) is called:**
a. Overriding
b. Objections
c. Overloading
d. Overwriting

### Answer
c. Overloading

### Explanation
Method overloading is the practice of creating multiple methods (or constructors) with the same name but different parameters. The parameters can differ in the number of parameters, the data type of parameters, or the order of parameters. Method overloading allows the same method name to be used for different purposes, and the appropriate method is selected at compile time based on the arguments passed to the method.

## Question 5
**Visibility (public versus private) in a class is important because**
a. It allows overloading methods.
b. It confuses students.
c. It allows creating new objects from a class.
d. It enforces encapsulation.

### Answer
d. It enforces encapsulation.

### Explanation
Visibility (public versus private) in a class is important because it enforces encapsulation. Encapsulation is a fundamental concept in object-oriented programming that involves restricting access to certain components of a class. By marking attributes as private, we prevent direct access to the object's internal state from outside the class. Public methods, including getters and setters, provide controlled access to the object's attributes and allow the object to perform specific actions. Encapsulation helps maintain data integrity and makes the code more robust and maintainable.

## Note Files 

- [M7_Part1_Methods-notes.txt](https://github.com/awakwe/CPlusPlus/blob/39760a6cc675ef2f2bc5bb814898d1e8bd54dfc8/M7_Part1_Methods-notes.txt)
- [M7_Strings_Math_notes.txt](https://github.com/awakwe/CPlusPlus/blob/39760a6cc675ef2f2bc5bb814898d1e8bd54dfc8/M7_Strings_Math_notes.txt)
- [M8_Part1_Intro_to_OOP_notes.txt](https://github.com/awakwe/CPlusPlus/blob/39760a6cc675ef2f2bc5bb814898d1e8bd54dfc8/M8_Part1_Intro_to_OOP_notes.txt)
- [M8_Part2_OOP_notes.txt](https://github.com/awakwe/CPlusPlus/blob/39760a6cc675ef2f2bc5bb814898d1e8bd54dfc8/M8_Part2_OOP_notes.txt)
- [Review-Slides-Part-2-notes.txt](https://github.com/awakwe/CPlusPlus/blob/39760a6cc675ef2f2bc5bb814898d1e8bd54dfc8/Review-Slides-Part-2-notes.txt)


## Quizzes

Throughout the module, there will be quizzes to test your knowledge on the topics we have covered. These quizzes will help you assess your understanding and identify areas where you may need to review.

> 📢 **Coming Soon!** We're currently working on providing detailed information for various tutoring subjects. Stay tuned for comprehensive explanations and examples. In the meantime, if you have any specific questions or need assistance, feel free to call, text, or email Tony Tutoring ASAP!


## Active Learning Strategies

During the virtual lecture, we will use active learning strategies to engage with the material and deepen our understanding. These strategies may include group discussions, problem-solving activities, and interactive simulations.

> 📢 **Coming Soon!** We're currently working on providing detailed information for various tutoring subjects. Stay tuned for comprehensive explanations and examples. In the meantime, if you have any specific questions or need assistance, feel free to call, text, or email Tony Tutoring ASAP!


## Conclusion

By the end of this module, you should have a strong foundation in Microsoft 365 and be able to apply your knowledge to solve real-world problems.

[preview-lia](https://raw.githubusercontent.com/awakwe/CPlusPlus/main/README.md)

[Preview-Lia](https://liascript.github.io/course/?https://raw.githubusercontent.com/awakwe/CPlusPlus/main/README.md)
