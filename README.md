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
| Function | :Description: |
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
| **ft\_memset()** | The ft\_memset() function writes len bytes of value c (converted to an unsigned char) to the string b. Returns it's first argument.|
| **ft\_bzero()** | The ft\_bzero() function writes n zeroed bytes to the string s.  If n is zero, ft\_bzero() does nothing.|
| **ft\_memcpy()** | The ft\_memcpy() function copies n bytes from memory area src to memory area dst.  If dst and src overlap, behavior is undefined. Returns the original value of dst.|
| **ft\_memccpy()** |The ft\_memccpy() function copies bytes from string src to string dst.  If the character c (as converted to an unsigned char) occurs in the string src, the copy stops and a pointer to the byte after the copy of c in the string dst is returned. Otherwise, n bytes are copied and a null pointer is returned.|
| **ft\_memmove()** | The ft\_memmove() function copies len bytes from strin src to dst. The two strings may overlap; the copy is always done in a non-destructive manner. Returns the original value of dst. |
| **ft\_memchr()** | The ft\_memchr() function locates the first occurence of c (converted to an unsigned char) in string s. Returns a pointer to the byte located, or NULL if no such byte exists within n bytes.) |
| **ft\_memcmp()** | The ft\_memcmp() function compares byte string s1 against byte string s2. Both strings are assumed to be n bytes long. Returns 0 if the first two strings are identical, otherwise returns the difference between the first two bytes (treated as unsigned char values). Zero-length strings are always identical.|
| **ft\_strlen()** | The ft\_strlen() function computes and returns the length of the string s.|
| **ft\_strdup()** | The ft\_strdup() function allocates sufficient memory for a copy of the string s1, does the copy, and returns a pointer to it.  The pointer may subsequently be used as an argument to the function free(3). If insufficient memory is available, NULL is returned.|
| **ft\_strcpy()** | The ft\_strcpy() function copies the string src to dst (including the terminating '\0' character.)|
| **ft\_strncpy()** |The ft\_strncpy() function copies at most len characters from src into dst.  If src is less than len characters long, the remainder of dst is filled with '\0' characters.|
| **ft\_strcat()** | The ft\_strcat() function appends a copy of the null-terminated string s2 to the end of the null-terminated string s1, then add a terminating '\0'. The string s1 must have sufficient space to hold the result.|
| **ft\_strncat()** | The ft\_strncat() function appends a copy of the null-terminated string s2 to the end of the null-terminated string s1. The ft\_strncat() function appends not more than n characters from s2, and then adds a terminating '\0'.|
| **ft\_strlcat()** | The ft\_strlcat() appends string src to the end of dst.  It will append at most maxlen - strlen(dst) - 1 characters.  It will then NUL-terminate, unless maxlen is 0 or the original dst string was longer than maxlen. maxlen should be the size of the destination string buffer dst plus the space for the nul-terminator. Returns the total length of the string it tried to create.|
| **ft\_strchr()** |The ft\_strchr() function locates the first occurrence of c (converted to a char) in the string pointed to by s.  The terminating null character is considered to be part of the string; therefore if c is '\0', the functions locate the terminating '\0'. Returns a pointer to the located character, or NULL if the character does not appear in the string.|
| **ft\_strrchr()** | The ft\_strrchr() function locates the last occurrence of c (converted to a char) in the string pointed to by s.  The terminating null character is considered to be part of the string; therefore if c is '\0', the functions locate the terminating '\0'. Returns a pointer to the located character, or NULL if the character does not appear in the string.|
| **ft\_strstr()** | The ft\_strstr() function locates the first occurrence of the null-terminated string needle in the null-terminated string haystack.|
| **ft\_strnstr()** | The ft\_strnstr() function locates the first occurrence of the null-terminated string needle in the null-terminated string haystack, where not more than len characters are searched. Characters after the '\0' are not searched. If needle is an empty string, haystack is returned; if needle occurs nowhere in haystack, NULL is returned; otherwise a pointer to the first character of the first occurrence of needle is returned.|
| **ft\_strcmp()** | The ft\_strcmp() function lexicographically compares the null-terminated strings s1 and s2. Returns an integer greater than, equal to, or less than 0, according as the string s1 is greater than,equal to, or less than the string s2.  The comparison is done using unsigned characters, so that '\200' is greater than '\0'.|
| **ft\_strncmp()** | The ft\_strncmp() function lexicographically compares the null-terminated strings s1 and s2. Returns an integer greater than, equal to, or less than 0, according as the string s1 is greater than, equal to, or less than the string s2.  Compares not more than n characters. The comparison is done using unsigned characters, so that '\200' is greater than '\0'.|
| **ft\_isalpha()** |The ft\_isalpha() function tests for any character for which isupper(3) or islower(3) is true.  The value of the argument must be representable as an unsigned char or the value of EOF. |
| **ft\_isdigit()** | The ft\_isdigit() function tests for a decimal digit character.  Regardless of locale, this includes the following characters only: '0' - '9'. |
| **ft\_isalnum()** | The ft\_isalnum() function tests for any character for which ft\_isalpha(3) or ft\_isdigit(3) is true.  The value of the argument must be representable as an unsigned char or the value of EOF. |
| **ft\_isascii()** | The ft\_isascii() function tests for an ASCII character, which is any character between 0 and decimal  127 inclusive. |
| **ft\_isprint()** | The ft\_isprint() function tests for any printing character, including space (' ').  The value of the argument must be representable as an unsigned char or the value of EOF. |
| **ft\_atoi()** | ft\_atoi() converts the initial portion of the string pointed to by str to int representation and returns the int. |
| **ft\_toupper()** | The ft\_toupper() function converts a lower-case letter to the corresponding upper-case letter.  The argument must be representable as an unsigned char or the value of EOF. If the argument is a lower-case letter, the ft\_toupper() function returns the corresponding upper-case letter if there is one; otherwise, the argument is returned unchanged. |
| **ft\_tolower()** | The ft\_tolower() function converts an upper-case letter to the correspond-ing lower-case letter.  The argument must be representable as an unsigned char or the value of EOF. |
