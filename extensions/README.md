## Extensions
This section includes the extensions i use on my Ubuntu 22.10

I manage all the extensions with 'Extension Manager' software on Ubuntu.

- ArcMenu - https://extensions.gnome.org/extension/3628/arcmenu/
- Blur my Shell - https://extensions.gnome.org/extension/3193/blur-my-shell/
- Caffeine - https://extensions.gnome.org/extension/517/caffeine/
- Compiz windows effect - https://extensions.gnome.org/extension/3210/compiz-windows-effect/
- Dash to Panel - https://extensions.gnome.org/extension/1160/dash-to-panel/


## Tweaks (Application in Gnome)

### Appearance

- Cursor: Vimix-white-cursors - [here](./Vimix-white-cursors/)
- Icons: Reversal-red-dark - [here](https://github.com/yeyushengfan258/Reversal-icon-theme)
- Shell: Catppuccin-Frappe-Purple - [here](./Catppuccin-Frappe-Purple/)
- Sound: Yaru - [already in system](#)
- Legacy Applications: Catppuccin-Frappe-Purple - [here](./Catppuccin-Frappe-Purple)

### Fonts 
All fonts are set to 'Hack Bold'. Can be found in [here](../kitty/ttf/Hack-Bold.ttf). You can set the size you desire ( between 9 - 11 )

### Startup Applications
I have enabled the 'Whell Scroll Speed' script because the movement of scroll was slow for me.

Script can be found [here](http://www.nicknorton.net/mousewheel.sh)

Instructions to install can be found [here](https://askubuntu.com/questions/255890/how-can-i-adjust-the-mouse-scroll-speed)

## Instructions
For applying theme and icons, you can check google. But in short it's putting the in `~/.themes` or 
`~/.icons` folder.

The above configurations are just the names , for better look you need to play with the values of extensions.

## Extra Ubuntu Setup

### Making passwordless sudo

- Edit sudoers file: `sudo nano /etc/sudoers`
- Find a line which contains `includedir /etc/sudoers.d`
- Below that line add: `username ALL=(ALL) NOPASSWD: ALL` , where username is your passwordless sudo username; Save your changes.
