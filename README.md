# 42 Lisboa's libft project.

Passed 3 peer evaluations and Moulinette's evaluation - scored 125 points.

Makefile includes rules to add bonus and a .Phony to prevent issues in case there are files with the same name as makefile rules.

## Mandatory Part

ft_atoi - convert a string to an integer.

ft_bzero - zero a byte string.

ft_calloc - allocates memory for an array. The memory is set to zero.

ft_memchr - zero a byte string.

ft_memcmp - compare memory areas
 
ft_memcpy - copy memory area. The memory areas must not overlap.

ft_memmove - copy memory area.

ft_memset - fill memory with a constant byte.

ft_isalnum - checks for an alphanumeric character.

ft_isalpha - checks for an alphabetic character.

ft_isascii - checks for a 7-bit unsigned char value that fits into the ASCII character set.

ft_isdigit - checks for a digit (0 through 9).

ft_isprint - checks for any printable character including space.

ft_strchr - locate character in string.

ft_strdup - duplicate a string.

ft_strlcat - appends the NUL-terminated string src to the end of dst.

ft_strlcpy - copies up to size - 1 characters from the NUL-terminated string src to dst.

ft_strlen - calculate the length of a string.

ft_strncmp - compare two strings.

ft_strnstr - locate a substring in a string.

ft_strrchr - locate character in string.

ft_tolower - convert uppercase letters to lowercase.

ft_toupper - convert lowercase letters to uppercase.

ft_substr

  

ft_strjoin

  

ft_strtrim

  

ft_split

  

ft_itoa

  

ft_strmapi

  

ft_striteri

  

ft_putchar_fd

  

ft_putstr_fd

  

ft_putendl_fd

  

ft_putnbr_fd

  

## Bonus Part

ft_lstnew - Allocates and returns a new node. The member variable ’content’ is initialized with the value of the parameter ’content’. The variable ’next’ is initialized to NULL.

ft_lstadd_front - Adds the node ’new’ at the beginning of the list.

ft_lstsize - Counts the number of nodes in a list.

ft_lstlast - Returns the last node of the list.

ft_lstadd_back - Adds the node ’new’ at the end of the list.

ft_lstdelone - Takes as a parameter a node and frees the memory of the node’s content using the function ’del’ given as a parameter and free the node. The memory of ’next’ is not be freed.

ft_lstclear - Deletes and frees the given node and every successor of that node, using the function ’del’. The pointer to the list is set to NULL.

ft_lstiter - Iterates the list ’lst’ and applies the function ’f’ on the content of each node.

ft_lstmap - Iterates the list ’lst’ and applies the function ’f’ on the content of each node. Creates a new list resulting of the successive applications of the function ’f’. The ’del’ function is used to delete the content of a node if needed.
