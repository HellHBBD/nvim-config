## Install

### Windows

```
md %LOCALAPPDATA%\nvim
cd %LOCALAPPDATA%\nvim
git clone https://github.com/HellHBBD/nvim-config.git .
```

### Linux

```
mkdir -p ~/.config/nvim
cd ~/.config/nvim
git clone https://github.com/HellHBBD/nvim-config.git .
```

install without permission

copy from [vim-plug](https://github.com/junegunn/vim-plug/blob/master/plug.vim) github

```
cp ~/.config/nvim/init.vim ~/.vimrc
mkdir -p ~/.vim/autoload/
cd ~/.vim/autoload/
vim plug.vim
```

## Uninstall

### Windows

```
rd %LOCALAPPDATA%\nvim
```

### Linux

```
rm -rf ~/.local/share/nvim
rm -rf ~/.config/nvim
```

uninstall without permission

```
rm ~/.vimrc
rm -rf ~/.vim
```