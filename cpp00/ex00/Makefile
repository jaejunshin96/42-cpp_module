NAME	= megaphone

CC		= c++
CFLAGS	= -Wall -Wextra -Werror -std=c++98

SRCS	= *.cpp

$(NAME):
	@$(CC) $(CFLAGS) $(SRCS) -o $(NAME)
	@echo "megaphone has been created."

all: $(NAME)

clean:
	@rm -f $(NAME)
	@echo "megaphone has been deleted."

fclean: clean

re: fclean all

.PHONY: all, clean, fclean, re
