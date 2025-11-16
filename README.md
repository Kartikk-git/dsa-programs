dsa-programs
A collection of Data Structures & Algorithms implementations in C. This repository contains readable, well-documented C programs demonstrating common DSA topics and useful utilities for learning and reference.

Contents
arrays/
linked-lists/
stacks-queues/
trees/
graphs/
sorting-searching/
dynamic-programming/
math/
utils/ Each folder contains C source files implementing algorithms or data structures, with example usage in comments.
Features
Plain C implementations (C11 compatible)
Small, focused programs for learning and testing
Clear comments describing problem, approach, complexity, and usage
Consistent naming and structure to make navigation easy
Getting started
Prerequisites

GCC (or another C compiler) supporting C11
Make (optional)
Compile a single file: gcc -std=c11 -Wall -Wextra path/to/file.c -o path/to/executable

Compile all .c files into bin/ (example): mkdir -p bin for f in $(find . -name "*.c"); do gcc -std=c11 -Wall -Wextra "
f
"
(basename "${f%.c}")" done

Run an executable: ./bin/your_program

File & naming conventions
Filenames: category_algorithm.c (e.g., arrays_binary_search.c)
Each file should include a header comment with:
Problem statement (short)
Time & space complexity
Example usage / sample input-output
Contributing
Contributions are welcome. Suggested workflow:

Fork the repo
Create a branch: git checkout -b feature/your-topic
Add your C file(s) following the naming and documentation conventions
Ensure code compiles cleanly with -Wall -Wextra
Open a pull request with a clear description of changes
Coding style:

Target C11
Meaningful names, modular functions
Keep functions small and documented
Avoid global state where possible
Testing
Include example input and expected output in file comments. If adding multiple related files, include a small test driver or instructions in the folder README.

License
MIT — see LICENSE file.

Contact
Repo owner: @Kartikk-git
