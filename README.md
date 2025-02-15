## fish-arch-motd-config
A message for each time you log into Friendly Interactive SHell (fish), designed on archlinux.

# Step by step guide
/path-to-file/file = where you have downloaded the available files 
Author of the fastfetch config file = https://github.com/CarterLi

Download the 2 files available ("config.jsonc" and "config.fish")
Most of these steps can be taken with a file manager.

1. Install fastfetch, figlet, fish and lolcat
>sudo pacman -S --noconfirm fish figlet fastfetch lolcat   

2. Make a directory on /etc/ for the fastfetch configuration file and put the config.jsonc (you have downloaded in this git repo) there 
>sudo mkdir /etc/fastfetch/; sudo mv /path-to-file/config.jsonc /etc/fastfetch/;

3. If there is a config.fish on ~/.config/fish/ delete it
>rm .config/fish/fish.config

4. Put the config.fish (you have downloaded in this git repo) on its correct path
>mv /path-to-file/config.fish ~/.config/fish/


If you want for other users (*within your system*) to have this motd (Message Of The Day) copy the config.fish on their respectives ~/.config/fish/ directories. Example:

    /home/user1/.config/fish/
    /home/user2/.config/fish/

!(https://github.com/user-attachments/assets/71298fb7-35d2-4351-870e-97c8585256fb)
![Demo](https://github.com/user-attachments/assets/796dcac2-ad9c-4c61-b6f1-31d8d33c318c)

# Explanation
This section is dedicated for those who dont want to do but to learn (or both).

### Abbreviations
>motd = Message Of The Day
>repo = Repositories
>

### Packages
fastfetch

    Its a pretty command that prints the main information of your system (also called system benchmarks) like distro, RAM, monitor resolution and more

figlet 

   ```Makes letters bigger. Much bigger. You give this command a word/phrase and it will "draw" the word/phrase bigger and print it (show it back to you).```

fish 
```A shell is one of the ways we communicate with the system - its the most powerful way. Fish is a shell but its made easier - it shows the preview of words youre typing and has a interactive menu for Tab/autocomplete options; two incredible functions.```

lolcat
```Makes rainbow text. You input text and it prints back with lots of colors in gradient```

### Image Analysis 
With what you read in mind you can now decrypt the image on the guide. 
```
Cool colors = lolcat
The big arch linux logo and system info = fastfetch
Big username = figlet
```

Note:
Fish permits to create this startup message so, although it doesnt look like, all of that is possible because of it.

### How it all fits together
If you want to replicate the image it will require your newfound concepts and reverse engineering.

Change config.fish file so we can customize the motd. Add figlet and lolcat (big letters and rainbows) to it.
Download the config for fastfetch and put in a directory the program reads from. 
Boom, youre finished.


GL with your ricing.
*See you in space, cowboy.* 

