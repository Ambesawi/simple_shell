# Simple Shell Project

## Introduction
This is the Simple Shell project, a command line interpreter developed in C as part of the ALX Software Engineering program. The Simple Shell mimics basic functionalities of a Unix shell, providing users with an interactive interface to execute commands.

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General
- Who designed and implemented the original Unix operating system
- Who wrote the first version of the UNIX shell
- Who invented the B programming language (the direct predecessor to the C programming language)
- Who is Ken Thompson
- How does a shell work
- What is a pid and a ppid
- How to manipulate the environment of the current process
- What is the difference between a function and a system call
- How to create processes
- What are the three prototypes of main
- How does the shell use the PATH to find the programs
- How to execute another program with the execve system call
- How to suspend the execution of a process until one of its children terminates
- What is EOF / “end-of-file”?

### Project-specific Objectives
- Implement a command line interpreter
- Handle command lines with arguments
- Handle the PATH to locate executable programs
- Implement built-in commands like `exit` and `env`
- Write your own getline function
- Handle logical operators `&&` and `||`
- Implement `cd`, `setenv`, and `unsetenv` built-ins
- Implement command separators `;`
- Implement file input mode for the shell
- Implement the `alias` built-in command
- Handle variables replacement (e.g., $? and $$)
- Handle comments in the shell (using `#`)
- Accept a file as input for batch processing

## Getting Started
To compile the Simple Shell, use the following command:

```bash
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
