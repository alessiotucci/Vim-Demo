# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: atucci <atucci@student.42.fr>              +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2024/10/08 14:27:22 by atucci            #+#    #+#              #
#    Updated: 2024/10/08 14:30:03 by atucci           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #


# Makefile to compile the example program
# Compiler
CC = gcc

# Compiler flags
CFLAGS = -Wall -Werror -Wextra

# Target executable
TARGET = example

all: $(TARGET)

$(TARGET): example.o
	$(CC) $(CFLAGS) -o $(TARGET) example.o

example.o: example.c
	$(CC) $(CFLAGS) -c example.c

clean:
	rm -f $(TARGET) example.o

