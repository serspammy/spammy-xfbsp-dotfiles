# spammy-i3wm-dotfiles
![image](https://github.com/user-attachments/assets/8f3c3659-7e90-425c-946e-1778b34bb5fb)
### this repo is outdated, if you're reading this then tell me to update it thanks!!!!
*required packages*: i3, jq, nitrogen, polybar, picom, rofi, brightnessctl, alacritty(or any terminal emulator that works with nerdfonts)

`$ sudo apt install i3 jq nitrogen polybar picom rofi brightnessctl alacritty`  (i've never used any distro other than mint so i don't know how other package managers are used, sorry)

-----

*nerd fonts used*: UbuntuMono, SauceCodePro, Iovseka

*custom polybar modules*: power and launcher (https://github.com/adi1090x/rofi)

*rofi theme*: https://github.com/adi1090x/rofi

*image viewer*: qimgv

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
