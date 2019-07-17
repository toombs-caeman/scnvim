my self-contained nvim configuration.

uses [git subrepo]() to include plugins

# Try it
``` bash
git clone https://github.com/toombs-caeman/scnvim
cd scnvim
./nvim
```

#TODO
* have nvim autoupdate nvim.appimage and pull the correct architecture
* break vim into a self contained subrepo
* theme with this: https://stackoverflow.com/questions/37400174/can-i-set-the-vim-colorscheme-from-the-command-line
    - this will leave the self contained theme intact when ricer isn't available
configure plugins:
* Plug looks pretty easy to use
* nvr https://github.com/mhinz/neovim-remote
    * https://hkupty.github.io/2016/Ditching-TMUX/
    * setup terminal escapes
* netwr
    - https://shapeshed.com/vim-netrw/#netrw-the-unloved-directory-browser
    - can be used to browse over ssh/mosh, inspect directories
    - https://kgrz.io/editing-files-over-network.html
* more at https://github.com/tpope/
    * commentary https://github.com/tpope/vim-commentary
    * git integration (vimagit/vim-fugitive)
* more at https://github.com/akrawchyk/awesome-vim
    * vim-indent-guides
    * targets.vim
    * vim-lastplace

other:
* syntax highlighting for
    * terraform
    * rustlang
    * golang  https://github.com/fatih/vim-go
* correct panel movement
* how to get the directory of the current file instead of where vim was opened for netwr?
* open links with xdg-open/lynx/elinks
* https://alex.dzyoba.com/blog/vim-revamp/
* sessions
* https://thoughtbot.com/blog/seamlessly-navigate-vim-and-tmux-splits
* vim sessions?
* default 'IDE' panels
* default file manager panels (netwr)
* https://github.com/rhysd/NyaoVim
