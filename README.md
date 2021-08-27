# BAShell


This repository contains the files for alx-Holberton's simple_shell project. It can be compiled using GCC and will execute a simple shell that can be used for some basic tasks and programs most commonly found in the $PATH.

## Pre-requisites
Authorized functions and macros:
- access (man 2 access)
- chdir (man 2 chdir)
- close (man 2 close)
- closedir (man 3 closedir)
- execve (man 2 execve)
- exit (man 3 exit)
- _exit (man 2 _exit)
- fflush (man 3 fflush)
- fork (man 2 fork)
- free (man 3 free)
- getcwd (man 3 getcwd)
- getline (man 3 getline)
- isatty (man 3 isatty)
- kill (man 2 kill)
- malloc (man 3 malloc)
- open (man 2 open)
- opendir (man 3 opendir)
- perror (man 3 perror)
- read (man 2 read)
- readdir (man 3 readdir)
- signal (man 2 signal)
- stat (__xstat) (man 2 stat)
- lstat (__lxstat) (man 2 lstat)
- fstat (__fxstat) (man 2 fstat)
- strtok (man 3 strtok)
- wait (man 2 wait)
- waitpid (man 2 waitpid)
- wait3 (man 2 wait3)
- wait4 (man 2 wait4)
- write (man 2 write)


### GCC command to compile:
```sh
gcc -Wall -Werror -Wextra -pedantic *.c -o BAShell
```


This wil compile all the '.c' files and change the output's name to 'BAShell'.
## Features

BAShell is a simple shell made in C to interact with a linux operating system.


## Test Output

#### It works both

Interactive mode:
```sh
firdaus$|./BAShell
BAShell$ ls
AUTHORS    builtin.c        main.c    shell.h
BAShell    extra_strings.c  memory.c  strings.c
README.md  extra_tools.c    parser.c  tools.c
BAShell$ exit
firdaus$|
```

#### Non-interactive mode:

```sh
$| echo "ls" | ./hsh
AUTHORS    builtin.c        main.c    shell.h
BAShell    extra_strings.c  memory.c  strings.c
README.md  extra_tools.c    parser.c  tools.c
$|
```

#### To exit program in interactive mode:

The output of this program when executed it look like:
```sh
exit
```

## Example

```sh
ls -l *.c
```

