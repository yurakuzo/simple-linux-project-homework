# Simple Program

## Overview
This is a simple C program that demonstrates using GNU Autotools to automate the build process. The program prints messages from both the main program and a function in another file.

## Prerequisites
- Autotools (`autoconf`, `automake`, etc.)
- A C compiler (e.g., `gcc`)

## Build and Install
1. Run `autoreconf -i` to generate the configuration files.
2. Run `./configure` to configure the project.
3. Run `make` to compile the program.
4. Run `make install` to install the program and its header.

## Cleanup
- Use `make clean` to remove compiled files.
- Use `make clean-all` to clean all generated files and remove installed binaries and headers.

## Usage
Once installed, you can run the program with:
```bash
simple_program

