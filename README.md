# my_zsh
ZSH config

# Initialization
Follow these steps to install and configure zsh as default shell  
First of all clone the project to your computer  
`git clone https://github.com/BoreaWolf/my_zsh.git .zsh`

Then update every submodule in the zsh directory  
`git submodule update --init`

Create a link to the config of zsh, in the user directory  
`ln -s .zsh/zshrc .zshrc`

Install zsh (depending on the distro you are using there will be a different packet manager)  
`sudo yum install zsh` (Fedora based)

Change the default shell with zsh  
`chsh -s $(which zsh)`

If using gnome-terminal, you need to change its default shell from its config.
