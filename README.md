## 🛠️ Fix “Escape” Key Not Exiting Insert Mode in Neovim

If pressing Esc doesn’t exit insert mode, try resetting your Neovim setup.

### 🔧 Steps

1. Remove your existing Neovim configuration and cache:
```
rm -rf ~/.config/nvim
rm -rf ~/.local/share/nvim
rm -rf ~/.cache/nvim
```

2. Reinstall your config (LazyVim Starter or your own):
```
git clone https://github.com/LazyVim/starter ~/.config/nvim
```

> Note: 💡 You can replace the repo URL with your own config if you have one.

3. Relaunch Neovim:
```
nvim
```
