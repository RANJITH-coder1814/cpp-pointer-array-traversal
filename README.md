# cpp-pointer-array-traversal
A basic C++ program that demonstrates pointer arithmetic while accessing elements of an array.

## 📌 Description
This repository contains a simple C++ program that explains how pointers work with arrays.
It shows how a pointer can move forward and backward to access different elements of an array.

## 🛠️ Technologies Used
- C++
- Pointer Arithmetic
- Arrays

## 📂 Program Code

```cpp
#include<iostream>
using namespace std;

int main(){
    int A[5] = {2, 4, 6, 8, 10};
    int *p = A;

    cout << *p << endl;   // First element
    p++;
    cout << *p << endl;   // Second element
    p--;
    cout << *p << endl;   // Back to first element

    return 0;
}
