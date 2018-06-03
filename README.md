# Repo to keep track of my neovim settings

After freshly installed neovim (or remove .config/nvim to reset), run the following
```
mkdir -p ~/.config/nvim
git clone https://github.com/kensyou/neovim_setting.git .

# install dein plugin
curl https://raw.githubusercontent.com/Shougo/dein.vim/master/bin/installer.sh > installer.sh
# For example, we just use `~/.cache/dein` as installation directory
sh ./installer.sh ~/.cache/dein

```

- follow instruction to add script in init.vim
- Use :call dein#install() to install plugin after saved
