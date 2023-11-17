# ft_printf

## Overview

`ft_printf` is a project that challenges you to implement your version of the standard C library function `printf`. This project is part of the Common Core curriculum at 42 Porto School.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Format Specifiers](#format-specifiers)
- [Example](#example)
- [License](#license)

## Introduction

The `ft_printf` project tasks you with recreating the behavior of the standard C library function `printf`. This function allows for formatted output, where you can specify various format specifiers to control the display of data.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Kelho0812/ft_printf.git
cd ft_printf
```

2. Build the project:

```bash
make
```

## Usage

To use `ft_printf`, include the `ft_printf.h` header file in your project. Call the function with the desired format string and additional arguments.

Example:

```c
#include "ft_printf.h"

int main(void)
{
    ft_printf("Hello, %s! The answer is %d.\n", "World", 42);
    return (0);
}
```

## Format Specifiers

The following format specifiers are supported in `ft_printf`:

- `%c`: Character
- `%s`: String
- `%p`: Pointer
- `%d` or `%i`: Signed integer
- `%u`: Unsigned integer
- `%x`: Hexadecimal (lowercase)
- `%X`: Hexadecimal (uppercase)
- `%%`: Percent sign

[INSERT ANY OTHER SPECIFIC FORMAT SPECIFIERS USED IN YOUR PROJECT]

## Example

```c
#include "ft_printf.h"

int main(void)
{
    int value = 42;
    char *str = "World";
    ft_printf("Hello, %s! The answer is %d.\n", str, value);
    return (0);
}
```

This will output:

```
Hello, World! The answer is 42.
```

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

---
