## Install to WSL2 or other Debian family
### 1. Install zsh
``` sh
sudo apt-get update
sudo apt-get install zsh -y
chsh -s /usr/bin/zsh
```
### 2. Install zinit
``` sh
bash -c "$(curl --fail --show-error --silent --location https://raw.githubusercontent.com/zdharma-continuum/zinit/HEAD/scripts/install.sh)"
```

### 3. Install chezmoi & apply dotfiles
``` sh
 sh -c "$(curl -fsLS https://chezmoi.io/get)" -- init --apply daigoro22
```

### 4. Install peco
``` sh
sudo apt install peco
```
