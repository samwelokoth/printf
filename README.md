

A custom implementation of the `printf` function in C, developed as a group project by Samwel Okoth and Paul Danso Asare.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## About

This repository contains a custom implementation of the `printf` function in C. It allows you to format and print text to the standard output according to a specified format string.

## Features

- Supports basic format specifiers: `%c`, `%s`, and `%%`.
- Counts the number of characters printed using `%n`.
- Lightweight and easy to use.

## Getting Started

### Prerequisites

- A C compiler (e.g., GCC)
- [Optional] A code editor or integrated development environment (IDE)

### Installation

1. Clone this repository to your local machine:

   ```shell
   git clone git@github.com:samwelokoth/printf.git
Compile the code using your C compiler:

shell

Usage
the following code will be compiled in the following way:
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c 

Include the custom printf function in your C code:

#include "custom_printf.h"
Call the my_printf function in your code just like you would with the standard printf function:

my_printf("Hello, %s!\n", "World");
Compile your program, including the custom printf implementation:

shell
gcc -o my_program my_program.c custom_printf.c
Run your program:

./my_program
Contributing
This is a group project, and we welcome contributions. The project is maintained by Samwel Okoth and Paul Danso Asare.

If you'd like to contribute, please follow these guidelines:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes.
Test your changes.
Submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Thanks to the C community for inspiration and support.






