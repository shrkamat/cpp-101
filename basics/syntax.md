---
title: Hello World
lang: cpp
code: exercises/hello-world.cpp
solution: solutions/hello-world.cpp
---

## Hello World

Let's write our first program in C++.

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

Above code introduces us to these concepts - 
1. main function
  * This is the entry point of the program.
2. header file
  * `#include <iostream>` is a preprocessor directive that includes the contents of the `iostream` header file in the program.
3. `std::cout`
  * This is an object of the `ostream` class. It is used to print the output to the standard output device.

Now if these concepts are new to you, it's highly go familiarize yourself with
`c++` basics before moving forward.

Add missing lines in the playground and check if you get the expected output.
