# 02 - Tech Talks | DevOps Series
> Bash/CLI/Shell Personalization (Install plugins and Addons on Windows Terminal & Ubuntu/Linux & Git & VScode & Powershell)



# Download & Install Nerd Fonts
> [Download NERD Fonts Manually](https://www.nerdfonts.com/font-downloads)

- Linux Bash Commands
  ```
  git clone --depth 1 https://github.com/ryanoasis/nerd-fonts
  cd nerd-fonts
  ```
  ```
  Install specific font:
  ./install.sh Hack
  ./install.sh JetBrainsMono
  ./install.sh Meslo
  or install all of them use:
  ./install.sh
  ```


# Install ZSH
  ```
  sudo apt install zsh
  ```
> https://www.zsh.org/


# Install Oh-My-Zsh
  ```
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
  ```
> https://ohmyz.sh/
> https://github.com/ohmyzsh/ohmyzsh


# Install ZSH Plugins
  Auto-Suggestions + Syntax Highlighting
  ```
  git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions 
  git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
  ```


# Activate ZSH Plugins
  Edit .zshrc file
   ```
  vi ~/.zshrc
  plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
  ```



- null
```
 curl -i http://localhost:PORT
```
