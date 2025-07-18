CC = clang
CFLAGS = -Wall -Wextra -pedantic #-Werror

SRC = MAIN/main.c
OBJ = $(SRC:.c=.o)
TARGET = biblecli

all: $(TARGET)
	@make clean
	@./$(TARGET)

$(TARGET): $(OBJ)
	$(CC) $(CFLAGS) -o $@ $^

clean:
	rm -f $(OBJ) 

.PHONY: all clean

