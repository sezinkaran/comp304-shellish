# comp304-shellish
COMP 304 - Assignment 1: Developing an interactive Unix-style operating system shell.
Sezin Karan
GitHub Repository:  https://github.com/sezinkaran/comp304-shellish.git

## Description
This project is an interactive Unix-style operating system shell called Shell-ish.

## Features
- Part I: Basic command execution using `fork()` and `execv()` with path resolution.
- PArt II: I/O redirection (`>`, `>>`, `<`) using `dup2()` and command piping (`|`)
- Part III-a: Built-in `cut` command with `-d` (delimiter) and `-f` (fields) options
- Part III-b: Built-in `chatroom` command using named pipes (FIFOs) for multi-user communication
- Part III-c: Custom Command `finfo`

## Custom Command: `finfo`
The `finfo` command is a custom addition to Shell-ish that provides detailed metadata about a specified file
- It utilizes the `stat` system call to retrieve file information
- File size (in bytes), permissions (octal format), owner ID, and the last modification timestamp.
- Usage:  `finfo <filename>`

## How to build and run
1. Compile the shell: "gcc -o shellish-skeleton shellish-skeleton.c"
2. To run: "./shellish-skeleton"

## Screenshots
Screenshots demonstrating all the features mentioned above can be found in the `/imgs` folder.
