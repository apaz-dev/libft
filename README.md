# 📚 Libft 

**Libft** my first 42madrid project.

## ✨ Project summary

This project consists of programming a library in C.
Your library will have a bunch of general purpose functions that your programs will rely on.

## 📖 Descripción de funciones

### 1. String functions 📏

These functions are essential for manipulating character strings and are based on the standard functions of the ```<string.h>```:

  -```ft_strlen```: Length of a string.
  
  -```ft_strcpy, ft_strncpy```: Copies one string into another.
    
  -```ft_strdup```: Duplicates a string in a new memory block.
     
  -```ft_strcat, ft_strncat```: Concatenates strings.
  
  -```ft_strchr, ft_strrchr```: Locate characters into a string.
  
  -```ft_strcmp, ft_strncmp```: Compares strings.
  
  -```ft_strstr, ft_strnstr```: Find substrings inside a string.

###  2. Memory Handling Functions 💾

These functions are useful for managing memory manually and are based on functions of ```<stdlib.h>```:

  -```ft_memset```: Fills a memory block with a specific value.
  
  -```ft_bzero```: Fills a memory block with zeros.
  
  -```ft_memcpy```: Copy memory from 1 location to another.
  
  -```ft_memmove```: Moves 1 block of memory (takes overlapping in consideration).
  
  -```ft_memchr```: Searches a byte in a block of memory.

  -```ft_memcmp```: Compares two memory blocks.
  
  -```ft_calloc```: Reserves and clears a memory block.
  
### 3. Converter Functions 🔄

Functions that transform data between different types:

  -```ft_atoi```: Converts a string to an integer.
  
  -```ft_itoa```: Converts an integer to a string.
  
  -```ft_tolower, ft_toupper```: Converts uppercase characters to lowercase and vice versa.

### 4. Character Verification Functions 🔍

These functions are used to verify character types:

  -```ft_isalpha```: Checks if the character is alphabetic.
  -```ft_isdigit```: Checks if the character is numeric.
  -```ft_isalnum```: Checks if the character is alphanumeric.
  -```ft_isascii```: Checks if the character is an ASCII character.
  -```ft_isprint```: Checks if the character is printable.

### 5. Additional Functions ✨

These supplementary functions complement the basic library:

  -```ft_substr```: Creates a substring from a given string.
  -```ft_strjoin```: Joins two strings into a new string.
  -```ft_strtrim```: Removes whitespace characters at the beginning and end of a string.
  -```ft_split```: Splits a string into substrings using a delimiter.
  -```ft_strmapi```: Applies a function to each character of a string, generating a new one.
  -```ft_putchar_fd```: Writes a character to a file descriptor.
  -```ft_putstr_fd```: Writes a string to a file descriptor.
  -```ft_putendl_fd```: Writes a string followed by a newline to a file descriptor.
  -```ft_putnbr_fd```: Writes a number to a file descriptor.

## ⚙️ Compilation

To compile the library, clone this repository and execute the command:

```C
make
```
