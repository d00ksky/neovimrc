# neovimrc
For installing neovim:

curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux64.tar.gz
sudo rm -rf /opt/nvim
sudo tar -C /opt -xzf nvim-linux64.tar.gz



After this step add this to ~/.bashrc:

export PATH="$PATH:/opt/nvim-linux64/bin"






My neovim config








After putting nvim into .config first you need to install packer

```
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

You need to be able to open .config/nvim with nvim . to see all files and then navigate to packer.lua

Then open nvim in nvim folder in .config, find packer.lua and do :so
then :PackerSync and you are ready to go.

You also need to do :Copilot setup if you want copilot.
For Copilot also install Node.js - https://nodejs.org/en/download/
Then :Copilot enable to enable it

Example command for nodejs:

curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt-get install -y nodejs

(change 20.x with newest version number)


