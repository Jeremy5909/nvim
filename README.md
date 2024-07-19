# About
my silly petite little neovim configuration, convoluted installation instructions because they are mostly for me.
# Installation
## First, install packer
`git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim`
## Next, clone the repository into the correct location
`git clone https://github.com/Jeremy5909/nvim.git ~/.config/`
## Next, source the packer file and install the packages
`nvim ~/.config/nvim/lua/jeremy/packer.lua`
`Skip through errors with the spacebar`
`:so`
`:PackerSync`
