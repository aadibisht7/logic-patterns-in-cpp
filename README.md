# C++ Pattern Programs

A collection of pattern programs implemented in C++ to practice loops, nested loops, and logical problem-solving.

## About

This repository contains different types of patterns built using:

* `while` loops
* Nested `while` loops
* Basic variables and counters
* Simple logical conditions

All patterns are implemented with a limited number of variables to focus on understanding the core logic and loop structure.

## Patterns

The repository includes:

* Number patterns
* Star patterns
* Square and rectangle patterns
* Triangle patterns
* Pyramid patterns
* Reverse patterns
* Space-based patterns
* Other variations

## Example

```cpp
#include <iostream>
using namespace std;

int main(){
    int n;
    cin >> n;

    int i = 1;
    while(i <= n){
        int j = 1;
        while(j <= n){
            cout << i << " ";
            j = j + 1;
        }
        cout << endl;
        i = i + 1;
    }
}
```

### Output

```text
1 1 1 1
2 2 2 2
3 3 3 3
4 4 4 4
```

## Purpose

The main goal of this repository is to build a strong understanding of loops and pattern logic, which helps develop problem-solving skills for DSA and competitive programming.

## Language

C++

---

Part of my C++ and DSA learning journey.
