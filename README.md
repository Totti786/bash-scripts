# Bash Scripts Repository

This repository contains a collection of Bash scripts for various tasks and utilities. Feel free to explore and use them as needed.
```
## Cloning the Repository

To clone this repository to your local machine, use the following command:

git clone https://https://github.com/totti786/bash-scripts
```


## Setting Permissions

After cloning the repository, you may need to set executable permissions for the scripts. Navigate to the repository directory and run:

```bash
cd bash-scripts
chmod +x <name_of_script>
```

or you could make all the scripts excutable by running 

```bash
cd bash-scripts
chmod +x *
```

## Installing Scripts

For easy access to the scripts, you can place them in `~/.local/bin`. To do this, follow these steps:

1. Create the `~/.local/bin` directory if it doesn’t already exist:

    ```bash
    mkdir -p ~/.local/bin
    ```

2. Move the scripts to `~/.local/bin`:

    ```bash
    mv <name_of_script> ~/.local/bin/
    ```

## Updating PATH

To ensure that the scripts can be executed from anywhere on your system, you need to add `~/.local/bin` to your `PATH` environment variable. If it’s not already included, you can add it by following these steps:


1. Open your shell configuration file in a text editor. For example, if you use `bash`, you might edit `~/.bashrc` (for zsh users you need to edit `.zshrc` instead):

    ```bash
    vim ~/.bashrc
    ```

2. Add the following line to the end of the file:

    ```bash
    export PATH="$HOME/.local/bin:$PATH"
    ```

3. Save the file and exit the text editor.

4. Apply the changes to your current session:

    ```bash
    source ~/.bashrc
    ```


## Contributing

If you have any improvements or fixes, feel free to submit a pull request or open an issue.

