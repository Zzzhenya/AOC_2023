NAME = queen

SRC = nqp.c

all: $(NAME)


$(NAME): $(SRC) Makefile
	clang -Wextra -Wall -Werror $(SRC) -o $(NAME)

fclean:
	rm -rf $(NAME)

