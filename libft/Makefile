# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: mmomeni <mmomeni@student.42.fr>            +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2023/03/21 18:30:23 by mmomeni           #+#    #+#              #
#    Updated: 2023/12/23 19:38:52 by mmomeni          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME=		libft.a
CFLAGS=		-Wall -Wextra -Werror
SRCS= 		ft_atoi.c ft_bzero.c ft_calloc.c ft_isalpha.c ft_isascii.c ft_isdigit.c\
 ft_isalnum.c ft_isprint.c ft_memchr.c ft_memcmp.c ft_memcpy.c ft_memmove.c\
  ft_memset.c ft_strchr.c ft_strdup.c ft_strlcat.c ft_strlcpy.c ft_strlen.c ft_strcpy.c ft_strisnum.c\
   ft_strncmp.c ft_strnstr.c ft_strrchr.c ft_strcount.c ft_strrmchr.c ft_tolower.c ft_toupper.c ft_substr.c\
    ft_strcmp.c ft_strjoin.c ft_strrepl.c ft_strtrim.c ft_split.c ft_itoa.c ft_strmapi.c ft_striteri.c ft_putchar_fd.c\
	ft_putstr_fd.c ft_putendl_fd.c ft_putnbr_fd.c get_next_line.c ft_vecnjoin.c ft_vecjoin.c\
	ft_veclen.c ft_vecfree.c ft_vecdup.c ft_vecadd.c ft_vecget.c
BONUS_SRCS=	ft_lstnew.c ft_lstadd_front.c ft_lstsize.c ft_lstlast.c ft_lstadd_back.c ft_lstdelone.c\
ft_lstclear.c ft_lstiter.c ft_lstmap.c
SRC_OBJS=	$(SRCS:.c=.o)
BONUS_OBJS=	$(BONUS_SRCS:.c=.o)
OBJS=		$(SRC_OBJS) $(BONUS_OBJS)

all: $(NAME)

$(NAME): $(OBJS)
	$(AR) $(ARFLAGS) $(NAME) $(OBJS)
	
bonus: $(OBJS)
	$(AR) $(ARFLAGS) $(NAME) $(OBJS)
	
clean:
	$(RM) $(OBJS)

fclean: clean
	$(RM) $(NAME)

re: fclean all

.PHONY: all clean fclean re bonus
