# Detecting buffer overflow

## About Running
- How to build : `gcc -fno-stack-protector -o buffer1 buffer1.c`
- How to run : `./buffer1`

## About local variable
- valid : to check for right copy between strings
- str1, str2 : to test buffer overflow with strcpy, gets functions

## About user function
- next_tag : initializes a string with "START"

## Note
- gets() function, has been denied of compiling by GCC compiler because of its vurnerablity.
- so if you want to compile with GCC compiler then, use  
	`$gcc -fno-stack-protector -o [elf name] [source file]`

