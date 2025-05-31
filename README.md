# spammy-i3wm-dotfiles
![image](https://github.com/user-attachments/assets/8f3c3659-7e90-425c-946e-1778b34bb5fb)
## stuff to install: i3 nitrogen polybar picom rofi alacritty
- i3 (duh)
- xfce4 (desktop environment)
- nitrogen (wallpaper)
- picom (EYE CANDY 🤑🤑🤑🤑)

## non-essentials for this rice:
- polybar (practically replaced by xfce4-panel, but an old configuration of mine exists if you want)
 - alacritty (or some other terminal that'll work with nerdfonts)
  - a nerd font (duh)
- rofi (replaced by xfce4-appfinder, but an old configuration of mine exists if you want)
- dunst (replaced by xfce4-notifyd. again, a config exists if you want)
- ~~[i3lock-color](https://github.com/Raymo111/i3lock-color) (replaced by xflock4/xfce4-screensaver, config exists but i never got it to work on startup. i don't know why it wouldn't work) (you probably need to build this from source btw unless you're on arch or whatever)~~
- i3lock-fancy

definitely not essential stuff:
- qimgv (image viewer with no menubar or whatever)
-----

nerd fonts used: UbuntuMono, SauceCodePro

custom polybar modules: power and launcher (https://github.com/adi1090x/rofi)

rofi theme: https://github.com/adi1090x/rofi

image viewer: qimgv

-----

**vv probably needs to be built from source if you're on a deb-based distro vv**

*i3lock-color* (i3lock fork for customization): https://github.com/Raymo111/i3lock-color

*picom version v12.5*: https://github.com/yshui/picom


# notes:

 **1. add yourself to the `video` group for brightnessctl to work without `sudo`** (there's probably a more graceful way of doing this but this is what works for me. if you have a preferred or outright better solution then please change the config accordingly)
 
 **2. the polybar weather module is not provided, follow the instructions given in https://github.com/Strix007/polybar-getweather** (or just use one that doesn't require an openweather account lol i should've tried looking for that myself)
 
 **3. press $mod+t to set a random wallpaper! they're located inside `~/.config/nitrogen/wallpapers`**

4. i wanted to have rofi fly in from the left as a sidebar but i couldn't get the window rule to work. genereally picom's new window rules make my head hurt so i just don't use them 💀
5. this is basically my first rice so some stuff might be messed up sorry!!!!
6. the rofi folder is heavily cut down, go to the rofi themes repo linked above for more themes and stuff to use
7. workspace switching animations don't seem to work a third of the time
