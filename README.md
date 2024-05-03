# shellbutsmaller

## Overview

Minishell is a simple UNIX shell implementation developed as part of the curriculum at 42 School. It provides basic command-line interface functionality similar to the standard shell.

## Features

- **Command Execution:** Executes commands entered by the user.
- **Built-in Commands:** Supports built-in commands such as `cd`, `echo`, `pwd`, etc.
- **Input/Output Redirection:** Allows input/output redirection using `<`, `>`, `>>` operators.
- **Pipeline Execution:** Supports command pipelines using `|` operator.
- **Environment Variable Expansion:** Supports expansion of environment variables in command arguments.

## Getting Started

### Prerequisites

- Make sure you have `gcc` compiler installed on your system.

### Installation

1. Clone the repository:

`git clone <repository-url>`

2. Navigate to the project directory:

`cd shellbutsmaller`


3. Build the Minishell executable:

`make`


### Usage

1. Run Minishell:

`./minishell`


2. Enter commands at the prompt and press Enter to execute them.

3. Use built-in commands such as `cd`, `echo`, `pwd`, etc., or run external commands.

### Features Overview

- **Command Execution:**

`$ ls`

- **Built-in Commands:**

`$ cd /path/to/directory
$ echo "Hello, world!"
$ pwd`


- **Input/Output Redirection:**

`$ ls > output.txt
$ cat < input.txt`


- **Pipeline Execution:**

`$ ls | grep .txt`


- **Environment Variable Expansion:**
  
`$ echo $PATH`

### Contributing

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name for your feature or bug fix.
3. Make your changes and commit them with clear and concise commit messages.
4. Push your changes to your fork.
5. Submit a pull request to the main repository explaining your changes.
