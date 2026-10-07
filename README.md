The book is available in HTML form at [https://mit-pdos.github.io/xv6-riscv-book/](https://mit-pdos.github.io/xv6-riscv-book/).

The book is available in PDF form at [https://mit-pdos.github.io/xv6-riscv-book/book.pdf](https://mit-pdos.github.io/xv6-riscv-book/book.pdf).

This edition of the book has been converted to LaTeX.
In order to build it, ensure you have a TeX distribution that contains
the `pdflatex` command. With that, you should be able to build the book
by running `make`, which will clone the OS itself and build the book
to `book.pdf` in the main directory.

Figures are drawn using `inkscape`.
## Proposed Architecture Components
 Architecture Component | Implementation Technique 
 1  Process Architecture | Document process creation, process states, PID management, scheduling, and context switching using the relevant xv6 source files and architecture documentation. 
 2  Memory Architecture | Document virtual memory, page tables, address translation, and physical memory management using the memory-management documentation and xv6 source code. 
 3  System Call Architecture | Document the flow of system calls from user programs to the kernel, including system call entry, handling, and return.|
 4  File System Architecture | Document files, directories, inodes, file descriptors, and the interaction between different file-system layers. 
 5  Trap and Interrupt Architecture | Document traps, interrupts, system-call entry, and transitions between user mode and kernel mode using the relevant xv6 architecture documentation. 
