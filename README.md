# Pointers-In-CPP
## Aim
To study about pointers and understand its usage in C++.
## Tools
Visual Studio Code
## Theory
Pointers in C++ are variables that store memory addresses as their values. They enable direct memory manipulation and are fundamental for various C++ features, including dynamic memory allocation and data structures.
•int* ptr; declares a pointer to an integer.
•ptr = &x; stores the address of variable x in the pointer ptr.
•*ptr is called the dereference operator. It gives us access to the value stored at the memory address ptr is pointing to.

The size of pointer in a system is equal for every pointer no matter what type of data it is pointing to. It does not depend on the type, but on operating system and CPU architecture. The size of pointers in C++ is 

8 bytes for a 64-bit System
4 bytes for a 32-bit System
The logic is simple: pointers store the addresses of the memory and in a computer, the maximum width of a memory address is determined by the CPU architecture. 
<img width="1000" height="416" alt="image" src="https://github.com/user-attachments/assets/a8275db6-3593-43d3-b683-d70c9124cd43" />
<img width="584" height="428" alt="image" src="https://github.com/user-attachments/assets/086e108d-572e-4ded-8050-02e433ae550e" />

### Uses Of Pointers
Pointers are a useful concept in C++ that allow direct access to memory addresses, providing greater control over memory and data manipulation. Below are some primary uses of pointers in C++:

•Dynamic Memory Allocation: Pointers allow memory to be allocated dynamically at runtime using operators like new and delete. This enables the creation of objects or arrays whose sizes are determined during execution.

•Implementing Data Structures: Pointers are used to implementing complex data structures such as linked lists, trees, and graphs, where elements are dynamically allocated and linked together.
Pass Arguments by Pointer: Pass the argument with their address and make changes in their value using pointer. So that the values get changed into the original argument.

## Algorithms
### Incrementing Data Types Using Pointers
### Revering An Array 
### Finding Difference Of Array Elements
### Reading/Printing A String
## Conclusion
We learnt the advantages and ways of using pointers in c++








Reference: https://www.geeksforgeeks.org/cpp/cpp-pointers/
