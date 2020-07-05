# Windows
## Vim
1. Install Vim
2. Install [vim-plug](https://github.com/junegunn/vim-plug)
3. Create symbolic link to vimrc (in powershell as an adminstrator)
    ```powershell
    New-Item -ItemType SymbolicLink -Path "~/.vimrc" -Target "~/rc/.vimrc"
    ```
