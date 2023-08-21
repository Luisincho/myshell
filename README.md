# MyShell Scripts

## Installation

To install MyShell, you can follow these steps:

1. Open your terminal.
2. Change to your home directory by running the following command:
    ```
    cd ~
    ```
3. Clone the MyShell repository by running the following command:
    ```
    git clone git@github.com:matiascaniete/myshell.git
    ```

## Configuration and Autocompletion in zsh

To enable autocompletion for the MyShell scripts in zsh, you need to add the following line to your `~/.zshrc` file:

```sh
fpath=(~/myshell/autocomplete $fpath)
```

## List of Commands

You can find the complete list of commands in the following documentation files:

- [COMMANDS.md](docs/COMMANDS.md)
- [confirm.md](docs/confirm.md)
- [gpt.md](docs/gpt.md)
- [mysh.md](docs/mysh.md)
