# libftprintf

A custom implementation of the `printf` function in C, providing formatted output conversion.

## Features

- Supports conversion specifiers: `%c`, `%s`, `%p`, `%d`, `%i`, `%u`, `%x`, `%X`, and `%%`.
- Handles null characters and strings.
- Custom memory management for string operations.

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/jguigli/ft_printf.git
   cd ft_printf
   ```

2. **Build the Library:**
   ```bash
   make
   ```

3. **Clean Build Files:**
   - Remove object files:
     ```bash
     make clean
     ```
   - Remove object files and the library:
     ```bash
     make fclean
     ```

4. **Rebuild the Library:**
   ```bash
   make re
   ```

## Usage

1. **Include the Header:**
   Ensure your source files include the `ft_printf.h` header:
   ```c
   #include "ft_printf.h"
   ```

2. **Link the Library:**
   Compile your program with the `libftprintf.a` library:
   ```bash
   gcc -o my_program my_program.c -L. -lftprintf
   ```

3. **Call `ft_printf`:**
   Use `ft_printf` in your code as you would use the standard `printf`:
   ```c
   ft_printf("Hello, %s!\n", "world");
   ```
