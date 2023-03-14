# C++ Program Structure

This section will cover syntactic concepts that are essential for writing your first C++ program.

Before getting started, let’s take a closer look at our _Hello World!_ example to see how a typical C++ program is structured.

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, World!";
    return 0
}

```

The program above simply prints the phrase _Hello, World!_ in the terminal. Here is a breakdown of how this task is achieved through C++:

## Preprocessor Directive

```cpp
#include <iostream>
```

The above line is a preprocessor directive, a special type of statement that starts with the `#` symbol and is examined before actual compilation.

The include keyword is used here to import libraries. Standard library names must be enclosed in angle brackets `< >`, whereas user-defined library names must be enclosed in double quotation marks `" "`.

The library being imported in this program is the `iostream` library, which stands for input/output stream. This library allows us to use `cout` ("_see out_") on line 5 and print the _Hello, World!_ message.
