# Monty

## The Monty language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

### Monty byte code files

Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument:

### Requirement

- All files are compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=c89
- All our files end with a new line
- A README.md file, at the root of the folder describes the project.
- Code is checked using betty-style.pl and betty-doc.pl
- We were allowed to use a maximum of one global variable
- No more than 5 functions per file
- We were allowed to use the C standard library
- The prototypes of all our functions were included in our header file called monty.h

### Compilation & Output
Code will be compiled this way:
>> $ gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty

