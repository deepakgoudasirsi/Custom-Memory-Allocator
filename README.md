# Custom-Memory-Allocator
This project implements a heap-based memory allocation system in C++, mimicking the functionality of the standard malloc function found in C. The system is designed to enhance memory management capabilities within custom applications by providing fine-grained control over memory allocation and deallocation.

Key Features:
Dynamic Memory Management: Utilizes the sbrk() system call to dynamically map memory, allowing for flexible and efficient memory allocation.
Coalescing Algorithm: Implements a coalescing algorithm to merge adjacent free memory blocks, reducing fragmentation and optimizing memory utilization.
Custom Heap Management: The system manages memory on the heap, providing a tailored solution for applications requiring specific memory management strategies.
This project serves as a foundation for understanding low-level memory management in C++ and offers insights into the inner workings of dynamic memory allocation, making it an excellent resource for those interested in computer architecture and systems programming.
