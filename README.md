# 42_Libft

42 school's first project, <em>libft</em>, is about learning how the usual `standard functions` of C programming work. You will do the coding of the functions and also learn about `library` and `Makefile`.

	🤓 These functions will be used in future projects, so more important than delivering is understanding it!

For detailed information, refer to the [**subject of this project**](https://github.com/yasminefontenele/42_Libft/blob/main/Libft.pdf).

##

## Some tips ;)

I had no programming background, so [**this playlist**](https://www.youtube.com/watch?v=ucupombJuUM&list=PL3ZslI15yo2r-gHJtjORRMRKMSNRpf7u5) explaining data structures helped me a lot throughout the project.

For conference, in addition to the main that I mad, I used [**francinette**](https://github.com/xicodomingues/francinette).

##

## Included Functions

### Mandatory Functions
The mandatory functions of libft are either functions from the standard C library or other useful functions. They are mostly useful for character, string and memory manipulation.

Functions to check and manipulate characters:
- ft_isalpha    - alphabetic character test.
- ft_isdigit    - decimal-digit character test.
- ft_isalnum    - alphanumeric character test.
- ft_isascii    - test for ASCII character.
- ft_isprint    - printing character test (space character inclusive).
- ft_toupper    - lower case to upper case letter conversion.
- ft_tolower    - upper case to lower case letter conversion.

Functions to manipulate strings:
- ft_strlen     - find length of string.
- ft_strlcpy    - copy strings.
- ft_strlcat    - concatenate strings (s2 into s1).
- ft_strchr     - locate character in string (first occurrence).
- ft_strrchr    - locate character in string (last occurence).
- ft_strncmp    - compare strings (size-bounded).
- ft_strnstr    - locate a substring in a string (size-bounded).
- ft_substr     - extract substring from string.
- ft_strjoin    - concatenate two strings into a new string (with malloc).
- ft_strtrim    - trim beginning and end of string with the specified characters.
- ft_split      - split string, with specified character as delimiter, into an array of strings.
- ft_strmapi    - create new string from modifying string with specified function.
- ft_striteri   - Applies the function f to each character of the string passed as argument.

Functions to manipulate memory:
- ft_calloc     - memory allocation(with 0).
- ft_memset     - write a byte to a byte string.
- ft_bzero      - write zeroes to a byte string.
- ft_memcpy     - copy memory area.
- ft_memmove    - copy byte string.
- ft_memchr     - locate byte in byte string.
- ft_memcmp     - compare byte string.
- ft_strdup     - save a copy of a string (with malloc).

Functions for numbers:
- ft_atoi     - convert ASCII string to integer.
- ft_itoa     - convert integer to ASCII string.

Functions to write to a file descriptor
- ft_putchar_fd - output a character to given file.
- ft_putstr_fd  - output string to given file.
- ft_putendl_fd - output string to given file with newline.
- ft_putnbr_fd  - output integer to given file.
				
### Bonus Functions
The bonus functions of libft deal with list manipulation.
- ft_lstnew       - create new list.
- ft_lstadd_front - add new element at beginning of list.
- ft_lstsize      - count elements of a list.
- ft_lstlast      - find last element of list.
- ft_lstadd_back  - add new element at end of list.
- ft_lstdelone    - delete element from list.
- ft_lstclear     - delete sequence of elements of list from a starting point.
- ft_lstiter      - apply function to content of all list's elements.
- ft_lstmap       - apply function to content of all list's elements into new list.
