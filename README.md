In this repository we put a solution for 0x19. c -stacks, queues- LIFO, FIFO group assignment
Done by :
 - Tigist Tafa,
 - Betelhem Assefa

More Info about the tasks

Data structures

Please use the following data structures for this project. Don’t forget to include them in your header file.

/**
 * struct stack_s - doubly linked list representation of a stack (or queue)
 * @n: integer
 * @prev: points to the previous element of the stack (or queue)
 * @next: points to the next element of the stack (or queue)
 *
 * Description: doubly linked list node structure
 * for stack, queues, LIFO, FIFO
 */
typedef struct stack_s
{
        int n;
        struct stack_s *prev;
        struct stack_s *next;
} stack_t;
/**
 * struct instruction_s - opcode and its function
 * @opcode: the opcode
 * @f: function to handle the opcode
 *
 * Description: opcode and its function
 * for stack, queues, LIFO, FIFO

Compilation & Output
Your code will be compiled this way:
$ gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty

The Monty language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

Tasks


0. push, pall

mandatory

Implement the push and pall opcode.
   
1. pint

mandatory

Implement the pint opcode.

2. pop

mandatory

Implement the pop opcode.
   
3. swap

mandatory

Implement the swap opcode.
   
4. add

mandatory

Implement the add opcode.
   
5. nop

mandatory

Implement the nop opcode.
   
6. sub

#advanced

Implement the sub opcode.
   
7. div

#advanced

Implement the div opcode.
   
8. mul

#advanced

Implement the mul opcode.
   
9. mod

#advanced

Implement the mod opcode.
   
10. comments

#advanced
   
11. pchar

#advanced

Implement the pchar opcode.

12. pstr

#advanced

Implement the pstr opcode.   

13. rotl

#advanced

Implement the rotl opcode.

14. rotr

#advanced

Implement the rotr opcode.
   
15. stack, queue

#advanced

Implement the stack and queue opcodes.
   
16. Brainf*ck

#advanced

Write a Brainf*ck script that prints School, followed by a new line.
   
17. Add two digits

#advanced

Add two digits given by the user.
   
18. Multiplication

#advanced

Multiply two digits given by the user.

19. Multiplication level up

#advanced

Multiply two digits given by the user.
