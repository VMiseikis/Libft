# Libft
**What is Libft?**

This project is about understanding how functions of the standard C library work, re-code them and create your own library, which will be used in the future 42 projects.

**Requirements:**
- All functions must have the same prototypes and behave like original ones
- Only 3 standart C library functions allowed: write(), malloc(), free()
- Code must be written according C98 standart
- Everything must compile with the flags -std=c98 -Wall -Wextra -Werror
- Code must comply with the norminette rules

**Project related documents:**
- [Subject pdf](https://github.com/VMiseikis/42-Course/blob/master/Subject%20PDFs/libft.en.subject.pdf) </br>
- [Normintte rules](https://github.com/VMiseikis/42-Course/blob/master/Norminette/en.norm.pdf)

## Usage

Clone repository:
```
git clone https://github.com/VMiseikis/Libft.git && cd Libft
```

Create library archive:
```
make
```

Include created library archive `libft.a` in to a project:
```
#include <libft.h>
```

## Implemented functions:
`ft_atoi` `ft_bzero` `ft_calloc` `ft_isalnum` `ft_isalpha` `ft_isascii` `ft_isdigit` `ft_isprint` `ft_itoa` `ft_lstadd_back`
`ft_lstadd_front` `ft_lstclear` `ft_lstdelone` `ft_lstiter` `ft_lstlast` `ft_lstmap` `ft_lstnew` `ft_lstsize` `ft_memchr`
`ft_memcmp` `ft_memcpy` `ft_memmove` `ft_memset` `ft_putchar_fd` `ft_putendl_fd` `ft_putnbr_fd` `ft_putstr_fd`  `ft_split`
`ft_strchr` `ft_strdup` `ft_striteri` `ft_strjoin` `ft_strlcat` `ft_strlcpy` `ft_strlen` `ft_strmapi` `ft_strncmp` `ft_strnstr`
`ft_strrchr` `ft_strtrim` `ft_substr` `ft_tolower` `ft_toupper`

## Grading:
<div align="center">
<img width="150" alt="" src="https://github.com/VMiseikis/42-Course/blob/master/Images/score_125_100.jpg">
</div>
