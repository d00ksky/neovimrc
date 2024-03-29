# neovimrc
My neovim config

After putting nvim into .config first you need to install packer

```
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

Then open nvim in nvim folder in .config, find packer.lua and do :so
then :PackerSync and you are ready to go.

You also need to do :Copilot setup if you want copilot. 
Then :Copilot enable to enable it
