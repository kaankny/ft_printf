# ft_printf

## Project Overview

The `ft_printf` project involves creating a custom implementation of the well-known `printf` function from the C standard library. This project will help you understand how variable arguments work in C and provide a solid foundation for future C projects. The custom `ft_printf` function will be a part of your `libft` library.

## Purpose

The purpose of this project is to create a custom `printf` function, named `ft_printf`, that replicates the functionality of the standard `printf` function. This includes handling various format specifiers and managing variable arguments.

## What You Will Learn

- How to handle variable arguments in C using the `stdarg` library.
- How to implement a function with similar functionality to a standard library function.
- How to manage formatted output in C.
- How to write modular and extensible code.

## Project Contents

### Required Part

The project requires the implementation of the `ft_printf` function, which should handle the following conversions:

- `%c` - Prints a single character.
- `%s` - Prints a string of characters.
- `%p` - Prints a pointer address in hexadecimal format.
- `%d` - Prints a decimal (base 10) number.
- `%i` - Prints an integer in base 10.
- `%u` - Prints an unsigned decimal (base 10) number.
- `%x` - Prints a number in hexadecimal (base 16) format using lowercase letters.
- `%X` - Prints a number in hexadecimal (base 16) format using uppercase letters.
- `%%` - Prints a percent sign.

### External Functions

You are allowed to use the following external functions:

- `malloc`
- `free`
- `write`
- `va_start`
- `va_arg`
- `va_copy`
- `va_end`

## Compilation

Use the provided `Makefile` to compile the project. The Makefile includes the following targets:

- `all`: Compile the library.
- `clean`: Remove object files.
- `fclean`: Remove object files and the library file.
- `re`: Recompile the library.
- `bonus`: Compile the bonus part of the project.

## Usage
After compiling the library, include ft_printf.h in your projects and link against libftprintf.a to use the ft_printf function provided by your library.

## Conclusion
The ft_printf project is an excellent opportunity to deepen your understanding of variable arguments and formatted output in C. By completing this project, you will improve your ability to implement complex functions and manage variable arguments effectively.
