# My Dotfiles (Windows + WSL)

My dotfiles for the Windows+WSL environment that i'm currently using. There are
only a few pieces to this environment workflow.

### vim (Windows / WSL)

On Windows:
```powershell
# install vim and add vim.exe to path
# install vim-plug https://github.com/junegunn/vim-plug
# TODO: automate this process.
```

On WSL Bash:
```sh
sudo apt-get update && sudo apt-get install vim
# install vim-plug https://github.com/junegunn/vim-plug
```

Then copy .vimrc file to the appropriate path


### alacritty

On Windows: Download and install Alacritty. Add to path if not added.

Copy the alacritty.yml file to the appropriate path.


### tmux

On WSL:
```sh
sudo apt-get update && sudo apt-get install tmux
```

Then copy .tmux.conf to the appropriate path


### .bashrc for WSL

On WSL: Copy .bashrc to `~/`



