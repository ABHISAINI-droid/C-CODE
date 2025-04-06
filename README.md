# ASCII Value Converter (Int to Char)

This is a simple C++ program that takes an integer as input and converts it into its corresponding ASCII character.

## Features

- Converts ASCII values (0–127) to characters
- Simple and beginner-friendly C++ code
- Easy to compile and run

## Code

```cpp
#include <iostream>
using namespace std;

int main() {
    int x;
    cout << "Enter the number: ";
    cin >> x;

    char y = (char)x;
    cout << "The ASCII character is: " << y;

    return 0;
}
