#******************************************************************************#
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: avolgin <marvin@42.fr>                     +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2017/10/26 15:09:52 by avolgin           #+#    #+#              #
#    Updated: 2018/02/06 13:43:35 by avolgin          ###   ########.fr        #
#                                                                              #
#******************************************************************************#

NAME = libft.a

SOURCE = ft_memccpy.c ft_memcpy.c ft_strncat.c ft_strcat.c ft_strncpy.c \
ft_strlen.c ft_strcpy.c ft_strdup.c ft_memmove.c ft_memchr.c \
ft_memcmp.c ft_memset.c ft_bzero.c ft_strlcat.c ft_strchr.c ft_strrchr.c \
ft_strstr.c ft_strnstr.c ft_strcmp.c ft_strncmp.c ft_atoi.c ft_isalpha.c \
ft_isdigit.c ft_isalnum.c ft_isascii.c ft_isprint.c ft_toupper.c ft_tolower.c \
ft_memalloc.c ft_memdel.c ft_strdel.c ft_strnew.c ft_strclr.c ft_striter.c \
ft_striteri.c ft_strmap.c ft_strmapi.c ft_strequ.c ft_strnequ.c ft_strsub.c \
ft_strjoin.c ft_strtrim.c ft_strsplit.c ft_itoa.c ft_reverse.c ft_intlen.c \
ft_strzero.c ft_putchar.c ft_putstr.c ft_putendl.c ft_putnbr.c \
ft_putchar_fd.c ft_putstr_fd.c ft_putendl_fd.c ft_putnbr_fd.c ft_lstnew.c \
ft_lstdelone.c ft_lstdel.c ft_lstadd.c ft_lstiter.c ft_lstmap.c \
ft_is_whitespace.c ft_pow.c ft_rot_n.c ft_itoa_unsigned.c \
ft_reverse.c ft_reverse.c ft_reverse_bitwise.c ft_itoa_base.c \
ft_itoa_base_10_8.c ft_itoa_base_10_16.c ft_itoa_base_10_16x.c \
ft_itoa_long.c ft_itoa_long_long.c  ft_strjoin.c \
ft_strjoin_del.c ft_strjoin_del_all.c ft_strjoin_del_dest.c \
ft_itoa_long_long.c ft_itoa_long_long_u.c count_bits.c \
ft_count_digits.c ft_swap_bits.c get_next_line.c

OBJECT = $(SOURCE:.c=.o)

OPTIONS = -c -I $(HEADER)

HEADER = ./includes/

FLAGS = -Wall -Wextra -Werror 

all: $(NAME)

$(NAME): $(OBJECT)
		@ar rc $(NAME) $(OBJECT) 
%.o: %.c
		@gcc -g $(FLAGS) -o $@ -c $< $(OPTIONS)
clean:
		/bin/rm -f $(OBJECT)
fclean: clean
		/bin/rm -f $(NAME)
re: fclean all

.PHONY: clean fclean
