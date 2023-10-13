# String Plus - A C Library for String Manipulation

String Plus is a powerful C library that provides a wide range of functions for string manipulation and text formatting. This library is designed to make working with strings in C easier and more efficient. It includes functions for searching, copying, comparing, and formatting strings, as well as custom scanning and printing functions.

## Table of Contents

1. [Introduction](#introduction)
2. [List of Functions](#list-of-functions)
   - [s21_memchr](#s21_memchr)
   - [s21_memcmp](#s21_memcmp)
   - [s21_memcpy](#s21_memcpy)
   - [s21_memset](#s21_memset)
   - [s21_strncat](#s21_strncat)
   - [s21_strchr](#s21_strchr)
   - [s21_strncmp](#s21_strncmp)
   - [s21_strncpy](#s21_strncpy)
   - [s21_strcspn](#s21_strcspn)
   - [s21_strerror](#s21_strerror)
   - [s21_strlen](#s21_strlen)
   - [s21_strpbrk](#s21_strpbrk)
   - [s21_strrchr](#s21_strrchr)
   - [s21_strstr](#s21_strstr)
   - [s21_strtok](#s21_strtok)
   - [s21_pointers](#s21_pointers)
   - [s21_to_upper](#s21_to_upper)
   - [s21_to_lower](#s21_to_lower)
   - [s21_insert](#s21_insert)
   - [s21_trim](#s21_trim)
   - [s21_sscanf](#s21_sscanf)
   - [s21_sputsf](#s21_sputsf)
3. [Support Functions](#support-functions)
   - [s21_isspace](#s21_isspace)
   - [s21_spec_s_scan](#s21_spec_s_scan)
   - [s21_spec_c_scan](#s21_spec_c_scan)
   - [s21_spec_i_scan](#s21_spec_i_scan)
   - [s21_spec_f_scan](#s21_spec_f_scan)
   - [s21_spec_u_scan](#s21_spec_u_scan)
   - [s21_spec_p_scan](#s21_spec_p_scan)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

String Plus is a versatile C library that simplifies working with strings and text. Whether you need to search for specific patterns, manipulate strings, or perform custom formatted input and output, String Plus has you covered. It's designed for efficiency, flexibility, and ease of use.

## List of Functions

### `s21_memchr`

Description: Search for a character in a memory block.

### `s21_memcmp`

Description: Compare two memory blocks.

### `s21_memcpy`

Description: Copy memory from one location to another.

### `s21_memset`

Description: Set a memory block to a specific value.

### `s21_strncat`

Description: Concatenate two strings, limiting the number of characters.

### `s21_strchr`

Description: Find the first occurrence of a character in a string.

### `s21_strncmp`

Description: Compare two strings up to a specified length.

### `s21_strncpy`

Description: Copy part of a string to another string.

### `s21_strcspn`

Description: Find the length of the initial segment of a string containing characters not in another string.

### `s21_strerror`

Description: Get an error message based on an error number.

### `s21_strlen`

Description: Calculate the length of a string.

### `s21_strpbrk`

Description: Find the first character in a string that matches any character in another string.

### `s21_strrchr`

Description: Find the last occurrence of a character in a string.

### `s21_strstr`

Description: Find the first occurrence of a substring in a string.

### `s21_strtok`

Description: Tokenize a string.

### `s21_pointers`

Description: Support function for custom scanning.

### `s21_to_upper`

Description: Convert a string to uppercase.

### `s21_to_lower`

Description: Convert a string to lowercase.

### `s21_insert`

Description: Insert a string into another string at a specific position.

### `s21_trim`

Description: Remove specified characters from the beginning and end of a string.

### `s21_sscanf`

Description: Custom formatted input function.

### `s21_sputsf`

Description: Custom formatted output function.

## Support Functions

In addition to the main functions, String Plus provides several support functions that are used internally by the library. These functions help in implementing the primary functionality and are not meant to be called directly in most cases.

## Usage

To use String Plus in your C programs, simply include the appropriate header files and call the functions as needed. Make sure to check the function descriptions and usage examples in the documentation.

```c
#include "s21_string.h"

int main() {
    char str[] = "Hello, World!";
    printf("Length of the string: %zu\n", s21_strlen(str));
    return 0;
}
```

## Contributing

Contributions to String Plus are welcome! If you have suggestions, improvements, or bug fixes, please open an issue or submit a pull request on the [GitHub repository](https://github.com/your-repo).

## License

String Plus is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute it as needed.
