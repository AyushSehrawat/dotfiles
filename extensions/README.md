## Extensions

### VSCode Extensions

- Catppuccin for VSCode
- Catppuccin Icons for VSCode
- Error Lens
- ESLint
- Github Copilot
- Github Copilot Voice
- Gitlens - Git supercharged
- Go
- Prettier - Code formatter
- Python
- rust-analyzer
- Snippet - by vscode-snippet
- Svelte 3 Snippets
- Svelte for VSCode
- Svelte Intellisense
- Tailwind CSS IntelliSense
- Thunder Client

### Fedora 38

This section includes the extensions i use on my Fedora 38

I manage all the extensions with 'Extension Manager' software on Fedora. Since it's gnome 44 on fedora 38 , most extensions are not available on extensions.gnome.org. So i have to edit the dconf settings to enable the installation of extensions which are unsupported.

Extensions i use on Fedora 38

- User Installed Extensions

  - Appindicator and KStatusNotifierItem Support ( fedora doesn't have this by default )
  - Blur my Shell
  - Caffeine
  - Clipboard Indicator
  - Compiz windows effect
  - Legacy (GTK3) Theme Scheme Auto Switcher ( for fixing the dark theme issue in some apps )
  - RunCat
  - User Themes

- System Extensions
  - Applications Menu
  - Background Logo
  - Places Status Indicator

There is imwheel startup application mentioned [here](#startup-applications)

Also checkout this video featuring some nice post installation steps - https://www.youtube.com/watch?v=a3ePEjpg3lU

### Ubuntu 22.10

This section includes the extensions i use on my Ubuntu 22.10

I manage all the extensions with 'Extension Manager' software on Ubuntu.

- ArcMenu - https://extensions.gnome.org/extension/3628/arcmenu/
- Blur my Shell - https://extensions.gnome.org/extension/3193/blur-my-shell/
- Caffeine - https://extensions.gnome.org/extension/517/caffeine/
- Compiz windows effect - https://extensions.gnome.org/extension/3210/compiz-windows-effect/
- Dash to Panel - https://extensions.gnome.org/extension/1160/dash-to-panel/
- RunCat - https://extensions.gnome.org/extension/2986/runcat/

#### Tweaks (Application in Gnome)

#### Appearance

- Cursor: Vimix-white-cursors - [here](https://github.com/vinceliuice/Vimix-cursors)
- Icons: Reversal-red-dark - [here](https://github.com/yeyushengfan258/Reversal-icon-theme)
- Shell: Catppuccin-Frappe-Purple - [here](https://github.com/catppuccin/gtk)
- Sound: Yaru - [already in system](#)
- Legacy Applications: Catppuccin-Frappe-Purple - [here](https://github.com/catppuccin/gtk)

#### Fonts

All fonts are set to 'Hack Bold'. Can be found in [here](../kitty/ttf/Hack-Bold.ttf). You can set the size you desire ( between 9 - 11 )

#### Startup Applications

I have enabled the 'Whell Scroll Speed' script because the movement of scroll was slow for me.

Script can be found [here](http://www.nicknorton.net/mousewheel.sh)

Instructions to install can be found [here](https://askubuntu.com/questions/255890/how-can-i-adjust-the-mouse-scroll-speed)

#### Instructions

For applying theme and icons, you can check google. But in short it's putting the in `~/.themes` or
`~/.icons` folder.

The above configurations are just the names , for better look you need to play with the values of extensions.

## Extra Ubuntu Setup

### Making passwordless sudo

- Edit sudoers file: `sudo nano /etc/sudoers` or `sudo visudo`
- Find a line which contains `includedir /etc/sudoers.d`
- Below that line add: `username ALL=(ALL) NOPASSWD: ALL` , where username is your passwordless sudo username; Save your changes.
