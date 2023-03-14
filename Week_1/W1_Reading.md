# Introduction to C++

Learn what makes C++ one of the most popular programming languages.

## What is C++?

C++ (pronounced see plus plus) is a programming language developed by Bjarne Stroustrup at Bell Labs in 1979. C++ was designed as an extension to the C language, which was well-known for its efficiency and cross-platform portability at the time. C++ adds object-oriented programming and many other new features to C.

## Why learn C++?

C++ brings a lot to the table for both new and experienced programmers. It is:

- Fast and flexible
- Well-supported and standardized
- Similar to other popular languages like Java and C#, which makes it easy for intermediate programmers to learn C++ quickly

## Applications of C++

Forty years after its creation, C++ is one of the world’s most popular programming languages. Not only is C++ fun to learn, but it also has many real-world applications such as:

- Graphical applications (eg. Adobe Photoshop)
- Video games (eg. League of Legends)
- Browsers (eg. Mozilla Firefox)

C++ is so popular today because it builds on the success of the C language. It is a powerful language that can be used to develop a variety of programs from video games to internet browsers.

## C++ Style Guide

Learn how to write clean C++ code.

The style of C++ code is just as important as syntax and semantics. This article will give you an overview of C++’s formatting conventions and some tips on writing clean C++ code.

Don’t worry if you can’t remember everything in this guide all at once; we will continue to reinforce specific style rules for each upcoming topic in the syllabus.

### Why Care About Style?

Style refers to the conventions that govern how we write code. A clean style keeps complex C++ code manageable and readable. To demonstrate the difference that style can make, look at the following two blocks of C++ code:

This code follows a good style:

```cpp
#include <iostream>
#include <string>

using namespace std;

// This program prints out “Hello World!”
int main() {
  string message = "Hello World!\n";
  cout << message;
  return 0;
}
```

This code follows a bad style:

```cpp
using namespace std;
#include    <iostream>
#include <string>
string M= "Hello World!\n";
int main() {    // Does some stuff
  cout << M;;  return (3);}
```

Unlike syntax and semantics, style is very much a subjective matter. For the sake of consistency, we will follow [Google’s C++ Style Guide]<https://google.github.io/styleguide/cppguide.html#cpplint> in this article and throughout this course.

Let’s learn some style tips that will take your C++ code to the next level!

### Include Statements

`include` statements give us access to functionalities from header file libraries. As a rule of thumb, include statements are mostly written at the beginning of any C++ program. **Include headers** should be listed in the following order:

1. C system headers
2. C++ standard library headers
3. User-defined libraries’ headers.

```cpp
// C system headers
#include <stdlib.h>

// C++ standard library headers
#include <iostream>

// User-defined headers
#include "foo/server/bar.h"

// The rest of your code goes here…
```
