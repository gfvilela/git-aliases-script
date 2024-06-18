# Git Aliases Script

This is a bash script that provides aliases for common Git commands, making your workflow easier and faster.

**Note:** Currently, this script has been tested and works on macOS. The Linux version is under development (WIP).

## Features

- `gst` - Displays the current status of the repository.
- `gps` - Pushes local changes to the remote repository.
- `gco` - Switches to a specific branch.
- `gcm` - Commits with a message.
- `gbr` - Lists all branches.
- `gad` - Adds files to the staging area.
- `gmg` - Merges a specific branch into the current branch.
- `gcl` - Clones a remote repository.
- `glg` - Displays the commit log in a graphical format.
- `gac` - Adds and commits with a message.
- `gnb` - Creates and switches to a new branch.
- `gpl` - Pulls the current branch.
- `galias` - Lists all Git aliases with their comments, commands, and usage examples (includes pagination).

## Installation

1. Download the installation script:

    ```sh
    curl -o install_git_aliases.sh https://raw.githubusercontent.com/your-username/git-aliases-script/main/install_git_aliases.sh
    ```

2. Make the installation script executable:

    ```sh
    chmod +x install_git_aliases.sh
    ```

3. Run the installation script:

    ```sh
    ./install_git_aliases.sh
    ```

## How to Use

### Help

To get help on any alias, use the `--help` option:

  ```sh
    gst --help
  ```
