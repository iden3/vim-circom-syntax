# Circom syntax highlighting for vim

This is a [circom](https://github.com/iden3/circom) syntax highlighting file
for vim, based on the vim 8.1 javascript syntax highlighting file.

## Installation in vim

Copy the syntax file to the vim syntax folder:
```
mkdir -p ~/.vim/syntax
cp syntax/circom.vim ~/.vim/syntax/circom.vim
```

Enable the circom syntax for files with circom extensions in your `~/.vimrc`
with the following line:
```
au BufRead,BufNewFile *.circom set filetype=circom
```

## Installation in neovim

Copy the syntax file to the neovim syntax folder:
```
mkdir -p ~/.config/nvim/syntax
cp syntax/circom.vim ~/.config/nvim/syntax/circom.vim
```

Enable the circom syntax for files with circom extensions in your `~/.config/nvim/init.vim`
with the following line:
```
au BufRead,BufNewFile *.circom set filetype=circom
```
