Set up after starting initial box:
``` bash
sudo apt install -y zsh zsh-autosuggestions zsh-syntax-highlighting fzf pipx git python3-dev build-essential btop
```

Set default shell to zsh:
``` bash
chsh -s "$(which zsh)"
```

Install fastfetch
``` bash
curl -LO https://github.com/fastfetch-cli/fastfetch/releases/latest/download/fastfetch-linux-amd64.deb; sudo apt install -y ./fastfetch-linux-amd64.deb rm fastfetch-linux-amd64.deb; fastfetch
```