**Samsung Risc-V**

Basic Details:

Name: Surabhi M R
College: Vidyavardhaka College of Engineering Mysore
Email id: surabhimr04@gmail.com

**Task 1: Task is to install all the essential tools such as Ubuntu on VMBox, Virtual Box, Visual C++**

**1. Install Ubuntu 20.04 LTS on Oracle Virtual Machine Box**

![1 installation](https://github.com/user-attachments/assets/9129b68f-1211-4ca1-82c1-4bfe99c72338)

C and RISC-V Labs
This repository demonstrates the processes involved in compiling C programs and generating assembly code using both a standard GCC compiler and a RISC-V GCC compiler. 
It includes comprehensive steps and  guide users through each stage of the compilation and debugging workflow.
![2 code](https://github.com/user-attachments/assets/95f94dbf-c789-48b4-8a22-d29ece090146)



**Steps to Compile a .c File :**

gcc sum_1ton.c

./a.out

![3  execution](https://github.com/user-attachments/assets/fa863575-8f1f-43fd-b889-75149bb70967)

**Verify the contents using the cat command:**

cat sum_1ton.c

![4](https://github.com/user-attachments/assets/9894356a-d877-433b-ae15-c8aecb497574)



**Compile the C program for RISC-V architecture using:**

riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum_1ton.o sum_1ton.c

riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c

**Disassemble the object file to view its assembly code using:**

riscv64-unknown-elf-objdump -d sum_1ton.o

![5](https://github.com/user-attachments/assets/b6389321-6265-4b22-a673-a1fe3415cba8)




**Commands:**

-O1: Enables basic optimization for better performance without significantly increasing compilation time.

-Ofast: Focuses on maximizing performance by enabling aggressive optimizations, potentially at the cost of standard compliance.





