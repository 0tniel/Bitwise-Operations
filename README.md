# Bitwise-Operations
This repository contains examples and explanations of bit manipulation and various bitwise operations implemented in C++. It is designed to help users understand and perform efficient low-level operations on binary data.
<br>
<br>
<p align="center">Experiment 4a</p>
<br>

## Aim
To study various types of bitwise operations

## Software Used
- Dev C++

## Theory
Bitwise Operators are the operators that are used to perform operations on the bit level of the integers. While performing this operation integers are considered as sequences of binary digits. In C++, we have various types of Bitwise Operators.
<br>
<br>
Types Of Bitwise Operators
<br>
<br>
1)Bitwise AND  (&) :- The & (bitwise AND) in C++ takes two numbers as operands and does AND on every bit of two numbers. The result of AND is 1 only if both bits are 1.  
<br>
<br>
2)Bitwise OR  (|) :- The | (bitwise OR) in C++ takes two numbers as operands and does OR on every bit of two numbers. The result of OR is 1 if any of the two bits is 1. 
<br>
<br>
3)Bitwise XOR  (^) :- The ^ (bitwise XOR) in C++ takes two numbers as operands and does XOR on every bit of two numbers. The result of XOR is 1 if the two bits are different.
<br>
<br>
4)Bitwise NOT  (~) :- The ~ (bitwise NOT) in C takes one number and inverts all bits of it.
<br>
<br>
5)Left Shift  (<<) :- The << (left shift) in C takes two numbers, the left shifts the bits of the first operand, and the second operand decides the number of places to shift.
<br>
<br>
6)Right Shift  (>>) : - The >> (right shift) in C takes two numbers, right shifts the bits of the first operand, and the second operand decides the number of places to shift. 
<br>
<br>

## Algorithm

Step 1: Start
<br>
Step 2: Declare Variables a and b
<br>
Step 3: Input a and b from the user
<br>
Step 4: Display Bitwise And of a and b (a&b)
<br>
Step 5: Display Bitwise Or of a and b (a|b)
<br>
Step 6: Display Bitwise XOR of a and b (a^b)
<br>
Step 7: Display Bitwise Not of a (~a)
<br>
Step 8: Display Bitwise Not of b (~b)
<br>
Step 9: Display Left Shift by 1 of a (a<<1)
<br>
Step 10: Display Right Shift by 1 of a (a>>1)
<br>
Step 11:End
<br>

## Code

```cpp
//Otniel Jhirad
//23070123069
//E&TC A3
#include <iostream>
using namespace std;
int main() {
    int a, b;
    cout << "Pls Enter A Number In Decimal: ";
    cin >> a;
    cout << "Pls Enter Another Number In Decimal: ";
    cin >> b;
    int binary_a = a;
    int binary_b = b;
    cout << "Bitwise AND: " << (binary_a & binary_b) << endl;
    cout << "Bitwise OR: " << (binary_a | binary_b) << endl;
    cout << "Bitwise Xor: " << (binary_a ^ binary_b) << endl;
    cout << "Bitwise Not of A: " << (~binary_a) << endl;
    cout << "Bitwise Not of B: " << (~binary_b) << endl;
    cout << "Left Shift of A: " << (binary_a << 1) << endl;
    cout << "Right Shift of A: " << (binary_a >> 1) << endl;
    return 0;
}
```

## Output

![image](https://github.com/user-attachments/assets/2b5c84c4-1c48-445a-9fdb-864632476dc3)

## Conclusion

Thus, we have learned the different bitwise operations.


<br>
<br>
<p align="center">Experiment 4b</p>
<br>
