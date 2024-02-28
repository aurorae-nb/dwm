# NoahBad's config of DWM!
This is a modified copy of Chris Titus' "dwm-titus" project with some other minor tweaks because I felt like it. These include mostly just floating windows, better keybinds, and the suckless status bar. To install, make sure you have libx11, libxft, libxinerama, xorg, base-devel, make, kitty, and thunar installed. Additionally, I add picom and change kitty's default config to 0.7 for the opacity among a couple other tweaks. 

## Installation
Use the terminal and `cd` into each subdirectory and run `sudo make clean install`. Following this, append 
`slstatus & exec dwm`
to your .xinitrc file. Additionally, you may run `curl -Ss https://starship.rs/install.sh|sh` to install starship and copy the kitty config file to `~/.config/kitty/`. From here one may install picom to get some pretty transparency. It may also be beneficial to install yay and github-cli for ease of use of the system alongside various other things. Installing feh and putting `. .fehbg &` at the top of your .xinitrc file will give your desktop a beautiful look after generating the file in question. This is done with `feh --bg-fill [PATH-TO-FILE]`.

## Theming
To install the nordic theme, I run `cd /usr/share/theme && sudo git clone https://github.com/EliverLara/Nordic` and set it with lxappearance. You can also install cursors and fonts to set the same way but when it comes to theme related things for Qt apps I guess all hope is lost lol. 
