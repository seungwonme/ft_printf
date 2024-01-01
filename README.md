# ft_printf

The `ft_printf` project is part of the 42 school curriculum, challenging students to implement their own version of the standard C library's `printf` function. This project aims to deepen understanding of variadic functions and improve string manipulation skills in C.

## Overview
The `ft_printf` function mimics the behavior of the standard `printf` function and supports a subset of its format specifiers. Key features include:

- String formatting: %s, %c, %d, %i, %u, %x, %X, %p, and more.
- Width and precision: Specifying field width and precision with the * or numeric values.
- sFlags: Supporting flags such as 0, -, +, (space), and #.
-
## Usage
1. Clone the project:
```bash
git clone https://github.com/seungwonme/ft_printf
```

2. Navigate to the project directory:
```bash
cd ft_printf && rm -rf .git
```

3. Compile the library:
```bash
make
```

4. Link the library in your project and include the header file:
```c
#include "ft_printf.h"

int main(void)
{
    ft_printf("Formatted output: %s %d\n", "Hello", 42);
    return 0;
}
```

- To clean up object files:
```bash
make clean
```

- To delete all build files:
```bash
make fclean
```

- To clean and rebuild the library:
```bash
make re
```

## Supported Format Specifiers
- `%c`: Character
- `%s`: String
- `%d` and `%i`: Signed decimal integer
- `%u`: Unsigned decimal integer
- `%x` and `%X`: Hexadecimal integer
- `%p`: Pointer address

For a complete list of supported features, refer to the ft_printf implementation.
