# fish-arch-motd-config
A message for each time you open the Friendly Interactive SHell (fish) designed on archlinux.

# Step by step guide
/path-to-file/file = where you have downloaded the available files 

Most of these steps can be made with a file manager.

1. Install fastfetch, figlet, fish, lolcat -> sudo pacman -S --noconfirm fish figlet fastfetch lolcat   
Author of the config file = https://github.com/CarterLi

2. Make a directory on /etc/ for fastfetch configuration file and put the config.jsonc there -> sudo mkdir /etc/fastfetch/; sudo mv /path-to-file/config.jsonc /etc/fastfetch/;

3. If there is a config.fish on ~/.config/fish/ delete it

4. Put the config.fish on its correct path -> mv /path-to-file/config.fish ~/.config/fish/


If you want for other users to have this motd (Message Of The Day) copy the config.fish on their respectives ~/.config/fish/ directories 
