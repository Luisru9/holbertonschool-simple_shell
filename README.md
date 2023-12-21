# Simple Shell

A basic shell program implemented in C.


---

## Introduction

The Simple Shell is a basic command-line interface implemented in C. It provides a minimalistic shell environment where users can enter commands, and the shell will execute them.

---

## Features

- Interactive command-line interface.
- Basic command execution.
- Built-in "exit" command to terminate the shell.

---

## Getting Started

### Prerequisites

- GCC compiler
- Linux environment (or similar)

### Installation

Clone the repository:

```bash
git clone https://github.com/Luisru9/holbertonschool-simple_shell.git

Navigate to the project directory:

cd simple_shell

Compile the code:

gcc hsh.c shell_func.c simple_shell.h -Wall -Werror -pedantic -std=gnu89 -o hsh

Run the shell:

./hsh
```

## Usage

Once the shell is running, you can enter commands and press Enter to execute them. To exit the shell, type "exit" and press Enter.

## Functions

### `main`

The main function initializes the shell environment, reads user input, and executes commands until the user enters "exit" or an error occurs.

### `trim`

Removes leading and trailing whitespace from a string.

### `free_token`

Frees memory allocated for token arrays and token strings.

### `free_paths_array`

Frees memory allocated for the paths array.

### `get_path`

Gets the full path of a command.

### `Tok`

Tokenizes a command string and executes it.

### `child_creator`

Creates a child process and executes the command.

---

## Authors

Luis Gonzalez Pagan
Manuel Morales