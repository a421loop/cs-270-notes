
## Reading Sept 3


Similarities to CS 167 or other programming experiences


This course feels familiar because it’s still about the core programming ideas—functions, loops, conditionals, and classes. 
The overall approach to problem-solving is the same. For example, the Euclidean algorithm for GCD works the same way whether it’s written in Python or C++.


Differences


The big changes explained in the reading and what we discussed in class come down to how C++ works as a language:
1) Compilation: Unlike Python, I can’t just run the file in C++; I have to compile it first before it executes.
2) Static typing: In C++, the programmer has to declare the type of everything (variables, parameters, return values), while Python just figures it out.
3) Memory management: C++ affords control with things like pointers and dynamic memory, but that also means the programmer is responsible for keeping track of it.
4) Syntax: The rules are stricter—semicolons, curly braces, header files, and just a lot more ways to write the same thing compared to Python.


Most interesting or confusing part of the reading


I thought the section on the compilation model was pretty interesting. It explained how C++ trades flexibility for efficiency—Python runs quickly and loosely, while C++ does the heavy checking up front when compiling. It makes sense why different languages are better for different situations.


Most interesting or confusing C++ feature


The part that stood out to me was how C++ forces you to declare types everywhere (like int age(19)). It’s stricter, but also helpful since the compiler can catch mistakes before the program even runs. What tripped me up was the different ways to initialize variables—int age = 19; vs. int age(19); and figuring out when each style is used
