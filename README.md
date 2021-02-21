# C-Shell

## Introduction

This is an implementation of a Linux shell written in C language.

## Run the shell

1. Clone this directory and `cd` into it.
2. Run the command `cc  shell.c -o shell`.
3. Run `./shell`.
4. Run any command in the shell. It can entail as many number of tabs and spaces, the shell accounts for those.
5. In order to exit, run `exit`.

## Features

 The following functions have been written explicitly in C.

* **cd**  - Change directory

* **pwd** - Present Working directory

* **mkdir** - Make a directory (Alerts if already exists)

* **rmdir** - Remove the directory (Alerts if no such file or directory)

* **echo** - Write arguments to the standard output

* **help** - Display instructions

* **date** - Current time and date
 
* **exit** - Exit the shell ; also works for **z**

Also supports running **other commands** (such as scripting commands like touch & cat, python, clear and ls)
