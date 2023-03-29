# dotfiles

dotfiles sync repo


## Homebrew

Google it

## iTerm2
- Download and install iTerm2 (google it)
- In iTerm2 - open preferences (cmd+,)
- Navigate to General/Preferences
- Check load preferences from a custom folder or URL
- Point it to `path/to/dotfilesRepo/iterm2`
- Restart iTerm2

There might be a problem with default path/colors or other profile values. If that happens:
- Navigate to Profiles
- Click `Other Actions`
- Select `Import JSON profiles`
- Make it default
- Restart iTerm2

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
PATH_TO_DOTFILES=~/Code/dotfiles
ln -s $PATH_TO_DOTFILES/.zshrc ~/.zshrc
ln -s $PATH_TO_DOTFILES/.gitconfig ~/.gitconfig
ln -s $PATH_TO_DOTFILES/.p10k.zsh ~/.p10k.zsh
```

## Powerlevel10k

```bash
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

## Powerline fonts

```bash
# clone
git clone https://github.com/powerline/fonts.git powerline-fonts --depth=1
# install
cd fonts
./install.sh
```


## zsh-syntax-highlighting
https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md#oh-my-zsh

## zsh-autosuggestions
https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh