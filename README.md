# spammy-xfbsp-dotfiles
| tiled layout | floating windows |
| -- | -- |
![tiled](https://github.com/user-attachments/assets/f86b233e-b4e6-4bb9-9ce3-8467de4973a2) | ![floating](https://github.com/user-attachments/assets/824ac0a2-795a-4621-bbfa-7e5091c74619)

### a mix of xfce and ~~i3wm~~ bspwm
basic setup instructions: https://gist.github.com/fathulfahmy/61910e84b99b38009ad9268811e4aa2a

--- 
### stuff to install
- bspwm (duh)
- xfce4 (desktop environment)
- nitrogen (wallpaper)
- picom (EYE CANDY 🤑🤑🤑🤑)

### non-essentials for this rice:
- rofi (replaced by xfce4-appfinder)
- dunst (replaced by xfce4-notifyd)
- polybar (replaced by xfce4-panel)
  - alacritty (or some other terminal that'll work with nerdfonts)
    - a nerd font (duh)
- ~~[i3lock-color](https://github.com/Raymo111/i3lock-color) (replaced by xflock4/xfce4-screensaver, config exists but i never got it to work on startup. i don't know why it wouldn't work) (you probably need to build this from source btw unless you're on arch or whatever)~~
- ~~i3lock-fancy (just use this one tbh)~~ replaced by xfce4-screensaver

#### other things in screenshots:
- qimgv (image viewer with no menubar or whatever)
- cmatrix
- cava
- cbonsai
- pipes.sh
- fastfetch
  - hyfetch for the gays
- fish
-----

### nerd fonts used:
- Ubuntu Medium (i3 titlebars, if you want them)
- JetbrainsMono (terminal font)

### rofi theme (not pictured): https://github.com/adi1090x/rofi

-----
### notes:

1. `$mod+t` to randomly switch wallpapers! walls should be located in `~/Pictures/wallpapers`
2. my `picom.conf` uses the old config style because windows rules make my head hurt. sorry if you don't like badly-written configuration
3. toggling resize mode will send a notification. not having an indicator when using a bar other than i3bar always bothered me
4. multiple i3 utilities (i.e. dmenu/rofi, dunst, i3bar) have been replaced with xfce4 tools, but they have old existing configurations you can use
5. you can use `xfce4-session-settings` to manage startup programs, but sometimes it doesn't work from my experience, so doing so using the i3 configuration is a working alternative
6. there are keybinds defined for `xfce4-screenshot`:
   - `Print` - takes a fullscreen screenshot
   - `Control+Print` - takes a screenshot of the selected region
   - `$mod+Print` - screenshots the current active window
   using these keybinds to take screenshots will send a notification and automatically save them to `~/Pictures` without a gui prompt, along with a filename corresponding to whether you took a fullscreen, region, or window screenshot

| saved screenshots | screenshot notifications|
| -- | -- |
![image](https://github.com/user-attachments/assets/2fa44e3c-e351-4e8d-892a-fd7df81f1fae) | ![image](https://github.com/user-attachments/assets/98117ff7-2b1e-4b7e-84f9-240d1ff7d36a)

