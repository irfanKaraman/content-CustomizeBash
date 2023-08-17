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


# Install Starship
  ```
  curl -sS https://starship.rs/install.sh | sh
  ```
> https://starship.rs/

# Activate Starship
  Edit .zshrc file and add this line
   ```
  vi ~/.zshrc
  eval "$(starship init zsh)"
  ```

# Install fzf (FuzzyFinder)
  ```
  git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
  ~/.fzf/install
  ```


# Install Bat
  ```
  sudo apt install bat
  ```
  edit starship.toml for alias
  ```
  alias cat='bat --paging=never'
  ```



- null
```
 curl -i http://localhost:PORT
```
