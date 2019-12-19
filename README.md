# C Libary (Libft)

### Table Of Contents
* [Objective](#objective)
* [Usage](#usage)
* [Personal Functions](#Personal-Functions)
* [Functions](#Standard-Functions-in-C-Libaries)

## Objective
* Very first project at 42, involving creating personal and useful useful functions as well as standard functions in C Libaries

## Usage

## Personal Functions
| Function | Description |
| :---: | :--- |
| ft_memalloc | |
| ft_memdel | |
| ft_strnew | |
| ft_strdel | |
| ft_strclr | |
| ft_strriter | |
| ft_striteri | |
| ft_strmap | |
| ft_strmapi | |
| ft_strequ | |
| ft_strnequ | |
| ft_strsub | |
| ft_strjoin | |
| ft_strtrim | |
| ft_strsplit | |
| ft_itoa | |
| ft_putchar | |
| ft_putstr | |
| ft_putendl | |
| ft_putnbr | |
| ft_putchar_fd | |
| ft_putstr_fd | |
| ft_putendl_fd | |
| ft_putnbr_fd | |
| ft_lstnew | |
| ft_lstdelone | |
| ft_lstdel | |
| ft_lstadd | |
| ft_lstiter | |
| ft_lstmap | |

## Standard Functions in C Libaries
| Function | Description |
| :---: | :--- |
| [**ft\_memset()**](https://github.com/michaelbrave/C-Standard-Library-Clone---42-libft/blob/master/src/ft_memset.c) | The ft\_memset() function writes len bytes of value c (converted to an unsigned char) to the string b. Returns it's first argument.|
| [**ft\_bzero()**](https://github.com/michaelbrave/C-Standard-Library-Clone---42-libft/blob/master/src/ft_bzero.c) | The ft\_bzero() function writes n zeroed bytes to the string s.  If n is zero, ft\_bzero() does nothing.|
| [**ft\_memcpy()**](https://github.com/michaelbrave/C-Standard-Library-Clone---42-libft/blob/master/src/ft_memcpy.c) | The ft\_memcpy() function copies n bytes from memory area src to memory area dst.  If dst and src overlap, behavior is undefined. Returns the original value of dst.|
| [**ft\_memccpy()**](https://github.com/michaelbrave/C-Standard-Library-Clone---42-libft/blob/master/src/ft_memccpy.c) |The ft\_memccpy() function copies bytes from string src to string dst.  If the character c (as converted to an unsigned char) occurs in the string src, the copy stops and a pointer to the byte after the copy of c in the string dst is returned. Otherwise, n bytes are copied and a null pointer is returned.|
| [**ft\_memmove()**](https://github.com/michaelbrave/C-Standard-Library-Clone---42-libft/blob/master/src/ft_memmove.c) | The ft\_memmove() function copies len bytes from strin src to dst. The two strings may overlap; the copy is always done in a non-destructive manner. Returns the original value of dst. |
| [**ft\_memchr()**](https://github.com/michaelbrave/C-Standard-Library-Clone---42-libft/blob/master/src/ft_memchr.c) | The ft\_memchr() function locates the first occurence of c (converted to an unsigned char) in string s. Returns a pointer to the byte located, or NULL if no such byte exists within n bytes.) |
| [**ft\_memcmp()**](https://github.com/michaelbrave/C-Standard-Library-Clone---42-libft/blob/master/src/ft_memcmp.c) | The ft\_memcmp() function compares byte string s1 against byte string s2. Both strings are assumed to be n bytes long. Returns 0 if the first two strings are identical, otherwise returns the difference between the first two bytes (treated as unsigned char values). Zero-length strings are always identical.|
| strlen | |
| strdup | |
| strcpy | |
| strncpy | |
| strcat | |
| strncat | |
| strlcat | |
| strrchr | |
| strstr | |
| strnstr | |
| strcmp | |
| strncmp | |
| atoi | |
| isalpha | |
| isdigit | |
| isalnum | |
| isascii | |
| isprint | |
| toupper | |
| tolower | |
