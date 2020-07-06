These are my personal dotfiles they're setup around using python for web development.
They're pretty heavily commented to make it easy for you to modify for your needs.

# FIRST
1. Clone Repo to your home directory
2. Follow OS specific instructions below

# Windows
## Vim
1. Install Vim
2. Install [vim-plug](https://github.com/junegunn/vim-plug)
3. Create symbolic link to vimrc (in powershell as an adminstrator)
    ```powershell
    New-Item -ItemType SymbolicLink -Path "~/.vimrc" -Target "~/rc/.vimrc"
    ```
4. Startup vim. Install plugins.
    ```
    :PlugInstall
    ```
# Ubuntu
1. Vim should already be installed
2. Create a symbolic link in your home directory to this repo's .vimrc
    ```shell
    ln -s ~/rc/.vimrc ~/.vimrc
    ```
