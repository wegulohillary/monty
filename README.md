Opcodes

push - Push an elements to the stack.

pop - Removes the top element of the stack.

pall - Prints all the values on the stack, starting from the top of the stack.

nop - Doesn’t do anything.

pint - Prints the value at the top of the stack, followed by a new line.

pchar - Prints the char at the top of the stack, followed by a new line.

pstr - Prints the string starting at the top of the stack, followed by a new line.

swap - Swaps the top two elements of the stack.

rotl - Rotates the stack to the top

rotr - Rotates the stack to the bottom

add - Adds the top two elements of the stack.

sub - Subtracts the top element of the stack from the second top element of the stack.

div - Divides the second top element of the stack by the top element of the stack.

mul - Multiplies the second top element of the stack with the top element of the stack.

mod - Computes the rest of the division of the second top element of the stack by the top element of the stack.

stack - Sets the format of the data to a stack (LIFO). This is the default behavior of the program.

queue - Sets the format of the data to a queue (FIFO).

Files description:

File	Description

main.c	The main function

math.c	Functions to produce a math result with some elements on the stack

monty.h	Header file that includes all the prototypes of the functions and the structures

moves.c	Functions to modify the elements on the stack

print.c	Functions to prints the elements on the stack

push-pop.c	Functions to add elements on queque or stack
