*This project has been created as part of the 42 curriculum by finoment.*

## Description

Libft is a custom C library developed as a first step into low-level programming at 42.
The goal of this project is to reimplement a set of standard C library functions, as well
as additional utility functions such as linked list manipulation.

This project helps build a strong understanding of memory management, pointers,
and basic data structures in C.

## Instruction

### Compilation

To compile the library, run :

```bash
make
```
This will generate a ```libft.a``` static library.

### Usage

Include the header in your C files : 
```#include "libft.h"```

Compile your project with : 
```bash
cc -Wall -Wextra -Werror main.c -L. -lft
```
## Resources

### Classic References 
- Linux manual pages (man malloc, free, write)   
- W3Schools — C programming tutorials  
- Tutorialspoint — C programming guides and references  
- Portfolio Courses (YouTube) 
- 42 Network subject PDFs and official documentation  

### AI Usage
AI tools were used as an educational aid to better understand the project requirements
and core C concepts. This includes asking the AI to explain Linux manual pages
(such as malloc, free, and write), in order to better understand their behavior and usage.

The AI was also used to clarify how singly linked lists work, including their memory
representation and pointer relationships. Additionally, explanations were requested
regarding Makefile structure, common rules, and best practices.

All code was implemented, tested, and debugged manually by the author.
The AI was used strictly for explanations and learning purposes, not for generating
final implementations.

## Library Overview

The Libft library is a custom implementation of essential C standard library functions,
along with additional utility functions and data structure helpers. It is divided into
three main parts, each targeting a specific aspect of C programming fundamentals.

### Part 1 – Libc Functions

This part includes reimplementations of commonly used functions from the C standard
library. These functions focus on string manipulation, memory handling, and basic
character checks.

Examples include:
- ft_strlen
- ft_memset
- ft_bzero
- ft_memcpy
- ft_strdup
- ft_atoi

### Part 2 – Additional Functions

This section contains additional utility functions that are not part of the standard C
library but are commonly used in C projects. These functions focus on string processing
and dynamic memory allocation.

Examples include:
- ft_substr
- ft_strjoin
- ft_strtrim
- ft_split
- ft_itoa

### Part 3 – Linked List Functions

The final part introduces functions to manipulate singly linked lists using a generic
t_list structure. These functions allow the creation, traversal, modification, and
destruction of linked lists.

Examples include:
- ft_lstnew
- ft_lstadd_front
- ft_lstadd_back
- ft_lstsize
- ft_lstlast
- ft_lstdelone
- ft_lstclear
- ft_lstiter
- ft_lstmap
