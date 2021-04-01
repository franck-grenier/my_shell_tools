# Installation

## Oh My Zsh

`sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

## My tools

```
git clone git@github.com:franck-grenier/my_shell_tools.git ~/ &&
mv ~/.bashrc ~/bashrc_save &&
ln -s ./my_shell_tools/.zshrc && 
ln -s ./my_shell_tools/.bashrc &&
ln -s ./my_shell_tools/.my_aliases &&
ln -s ./my_shell_tools/.gitconfig
```

# Change shell

`chsh -s $(which zsh)`


