# 0x11. C - printf

This is a group project for the ALX School's C programming curriculum. The project aims to implement a custom version of the `printf` function in C. The custom `_printf` function will produce output according to a given format, similar to the standard `printf` function.

## Project Details

- **Team:** zeelshaday kibru, Hezron Njoroge
- **Project Start:** Aug 18, 2023 6:00 AM
- **Project Deadline:** Aug 23, 2023 6:00 AM
- **Checker Release:** Aug 19, 2023 12:00 PM
- **Auto Review:** Will be launched at the deadline

## Concepts

Throughout this project, the following concepts are expected to be understood and applied:

- Group Projects
- Pair Programming
- Flowcharts
- Technical Writing

## Background Context

The main objective of this project is to write a custom `printf` function in C. The function should handle various format specifiers and produce output accordingly.

## Resources

To successfully complete this project, the following resources are recommended:

- Secrets of `printf`
- Group Projects concept page
- Flowcharts concept page
- `man` pages:
  - `printf (3)`

## Requirements

### General

- Allowed editors: vi, vim, emacs
- Code will be compiled on Ubuntu 20.04 LTS using gcc with the following flags: `-Wall -Werror -Wextra -pedantic -std=gnu89`
- A `README.md` file at the root of the project folder is mandatory
- Code should follow the Betty style, as checked by `betty-style.pl` and `betty-doc.pl`
- Usage of global variables is not allowed
- Each file should contain no more than 5 functions
- Your code should be accompanied by a header file named `main.h` containing function prototypes
- All header files should be include guarded
- Do not use the `_putchar` function provided in previous projects

### GitHub

- Each project group should maintain a single repository
- Other team members should not fork or clone the repository to avoid scoring issues

### Compilation

Code will be compiled as follows:

```bash
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c
```

Do not include any `main` functions in files in the root directory. A separate folder for test files is recommended.

## Tasks

### 0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life

Write a function `int _printf(const char *format, ...)` that produces output according to a given format. The function should return the number of characters printed, excluding the null byte used to end output to strings. Output should be written to `stdout`.

The following conversion specifiers should be handled:

- `%c`: Character
- `%s`: String
- `%%`: Percent sign

Note that buffer handling, flag characters, field width, precision, and length modifiers are not required for this task.

### 1. Education is when you read the fine print. Experience is what you get if you don't

Extend the `_printf` function to handle the following conversion specifiers:

- `%d`: Decimal
- `%i`: Integer

Similar to the previous task, you do not need to handle flag characters, field width, precision, or length modifiers.

## Copyright

This project is the intellectual property of ALX School.
