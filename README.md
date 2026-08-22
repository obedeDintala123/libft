*This project has been created as part of the 42 curriculum by obdintal*
# Libft

## Description
This project involves creating a custom C library called **Libft**. The goal is to reimplement, from scratch, various functions found in the **C standard library (Libc)**, such as those for string manipulation, memory management, and type conversion. In addition to these, the library includes additional functions not found in the **C standard library (Libc)**, designed for more complex tasks involving advanced string manipulation and the implementation of linked lists.

---

## Libft Functions
Below are the functions available in the library and their purposes.

#### Character checking (ctype)
- `ft_isalnum.c` — checks if a character is alphanumeric
- `ft_isalpha.c` — checks if a character is alphabetic
- `ft_isascii.c` — checks if a character is ASCII
- `ft_isdigit.c` — checks if a character is a digit
- `ft_isprint.c` — checks if a character is printable
- `ft_toupper.c` — converts a character to uppercase
- `ft_tolower.c` — converts a character to lowercase

#### Memory manipulation
- `ft_memset.c` — fills a block of memory
- `ft_bzero.c` — zeroes out a block of memory
- `ft_memcpy.c` — copies memory
- `ft_memmove.c` — copies memory with safe overlap handling
- `ft_memchr.c` — searches for a byte in memory
- `ft_memcmp.c` — compares blocks of memory
- `ft_calloc.c` — allocates and zeroes out memory

#### String manipulation
- `ft_strlen.c` — returns the length of a string
- `ft_strchr.c` — searches for a character (from the start)
- `ft_strrchr.c` — searches for a character (from the end)
- `ft_strncmp.c` — compares strings (up to n characters)
- `ft_strnstr.c` — searches for a substring (up to n characters)
- `ft_strdup.c` — duplicates a string
- `ft_strlcpy.c` — copies a string with a size limit
- `ft_strlcat.c` — concatenates a string with a size limit
- `ft_strjoin.c` — joins two strings
- `ft_strtrim.c` — trims characters from both ends of a string
- `ft_strmapi.c` — applies a function to each character (returns a new string)
- `ft_striteri.c` — applies a function to each character (in-place)
- `ft_substr.c` — extracts a substring
- `ft_split.c` — splits a string by a delimiter

#### Conversion
- `ft_atoi.c` — converts a string to an integer
- `ft_itoa.c` — converts an integer to a string

#### Output (file descriptor)
- `ft_putchar_fd.c` — prints a character
- `ft_putstr_fd.c` — prints a string
- `ft_putendl_fd.c` — prints a string followed by a newline
- `ft_putnbr_fd.c` — prints a number

#### Linked lists
- `ft_lstnew.c` — creates a new node
- `ft_lstadd_front.c` — adds a node to the front of the list
- `ft_lstadd_back.c` — adds a node to the back of the list
- `ft_lstsize.c` — returns the size of the list
- `ft_lstlast.c` — returns the last node of the list
- `ft_lstdelone.c` — deletes a single node
- `ft_lstclear.c` — deletes the entire list
- `ft_lstiter.c` — applies a function to each node
- `ft_lstmap.c` — applies a function and creates a new list

---

## Instructions
To Compile the code, run: 
```bash
make
```

To clean the object files, run:
```bash
make clean
```

To clean the object files and library, run:
```bash
make fclean
```

To recompile the code, run:
```bash
make re
```

To use this library, run:
```bash
cc main.c -L. -lft -o programa
```
---

## Resources
- [W3Schools](https://www.w3schools.com) — general programming references and tutorials
- [Linux Man Pages](https://man7.org/linux/man-pages/) — manual pages for standard C library functions
- [Algoritmos - IME/USP](https://www.ime.usp.br/~pf/algoritmos/aulas/lista.html) — reference on linked lists
---

## AI Usage

This project made use of AI tools (ChatGPT/Claude) for:
- Clarifying documentation and man pages
- Debugging support and explaining error messages
- Reviewing code style and readability
- Creating illustrative guides on specific topics
