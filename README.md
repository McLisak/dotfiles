# dotfiles

dotfiles sync repo


## Homebrew

Google it

## iTerm2
- Download and install iTerm2 (google it)
- In iTerm2 open preferences (cmd+,)
- Navigate to General/Preferences
- Check load preferences from a custom folder or URL
- Point it to `path/to/dotfilesRepo/iterm2`

## ZSH

```bash
brew install zsh
```

## Oh-My-ZSH

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Symlinks

```bash
# Change below path
PATH_TO_DOTFILES = ~/Code/dotfiles
ln -s $PATH_TO_DOTFILES/.zshrc ~/.zshrc
ln -s $PATH_TO_DOTFILES/.gitconfig ~/.gitconfig
```

## Powerlevel9k/Powerlevel10k

```bash
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

## Powerline fonts

```bash
# clone
git clone https://github.com/powerline/fonts.git --depth=1
# install
cd fonts
./install.sh
```


## zsh-syntax-highlighting
```bash
brew install zsh-syntax-highlighting
```

## zsh-autosuggestions

```bash
brew install zsh-autosuggestions
```