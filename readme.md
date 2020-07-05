These are my personal dotfiles they're setup around using python for web development.
They're pretty heavily commented to make it easy for you to modify for your needs.

# FIRST
1. Clone Repo to your home directory
2. Follow OS specific instructions below

# Windows
## Vim
1. Install Vim
    * Note, to use autocompletion via the YouCompleteMePlugin
        * Install [choco](https://chocolatey.org/install)
        * Use choco in powershell as an adminstrator:
            ```powershell
            choco install vim
            choco install cmake
            choco install python3
            choco install golang
            choco install nodejs.install
            choco install visualstudio2019buildtools
            choco install visualstudio2019-workload-vctools
            ```
2. Install [vim-plug](https://github.com/junegunn/vim-plug)
3. Create symbolic link to vimrc (in powershell as an adminstrator)
    ```powershell
    New-Item -ItemType SymbolicLink -Path "~/.vimrc" -Target "~/rc/.vimrc"
    ```
4. YouCompleteMe Install (Optional) cmd as administrator
    * ```shell
       cd %USERPROFILE%/vimfiles/plugged/YouCompleteMe
    * [compile](https://github.com/ycm-core/YouCompleteMe#windows)

# Ubuntu
1. Vim should already be installed
2. ```shell
    ln -s ~/rc/.vimrc ~/.vimrc
    ```
