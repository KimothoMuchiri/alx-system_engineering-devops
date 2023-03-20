## The C Preprocessor

The C preprocessor **modifies a source code file before handing it over to the compiler**. You're most likely used to using the preprocessor 
to include files directly into other files, or **#define constants**, but the preprocessor can also be used to create "inlined" code using macros 
expanded at compile time and to prevent code from being compiled twice.

There are essentially three uses of the **preprocessor--directives, constants**, and macros. Directives are commands that tell the preprocessor to 
skip part of a file, include another file, or define a constant or macro. Directives always begin with a sharp sign (#) and for readability should be
placed flush to the left of the page. All other uses of the preprocessor involve processing #define'd constants or macros. Typically, constants and macros 
are written in ALL CAPS to indicate they are special

Table of contents and Files Description

0-object_like_macro.h Header file.

0-object_like_macro.h File that defines a macro named SIZE as an abbreviation for the token 1024.

1-pi.h File that defines a macro named PI as an abbreviation for the token 3.14159265359.

2-main.c Prints the name of the file it was compiled from, followed by a new line.

3-function_like_macro.h Function-like macro ABS(x) that computes the absolute value of a number x.

4-sum.h Function-like macro SUM(x, y) that computes the sum of the numbers x and y
