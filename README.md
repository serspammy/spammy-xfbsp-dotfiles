# spammy-xfbsp-dotfiles
| tiled layout | floating windows |
| -- | -- |
![tiled](screenshots/tiled2.png) | ![floating](screenshots/floating2.png)

## a mix of xfce and bspwm
### setup instructions:
0. go to `/usr/share/doc/bspwm/` and copy `bspwmrc` and `sxhkdrc` to `~/.config/bspwm/` and `~/.config/sxhkd/` respectively

if `/usr/share/doc/bspwm/` doesn't exist, get the sample configurations from [here](https://github.com/baskerville/bspwm/tree/master/examples) instead

1. open **Keyboard**, and go to **Application Shortcuts**
2. remove all shortcuts, as they will be handled by sxhkd instead
3. open **Session and Startup**
4. go to **Current Session**
5. for xfwm4 and xfce4-panel, set restart style to **never**
6. go to **Application Autostart**
7. add entries for bspwm, picom and xfce4-panel:
```
Name: BSPWM
Description: Binary Space Partitioning Window Manager
Command: bspwm
Trigger: on login

Name: Picom
Description: x11 compositing manager
Command: picom -b
Trigger: on login

Name: Xfce Panel
Description: Panel for the Xfce Desktop Environment
Command: xfce4-panel
Trigger: on login
```
sxhkd will automatically run alongside bspwm, no need to make an entry for that. optionally, you could actually just use keyboard settings for shortcuts, and forego sxhkd, but i find using sxhkd a little more convenient

the reason we have to disable xfce4-panel in 'Current Session', only to make a startup entry for it, is because leaving it like that would have the panel be invisible while still running. this is a workaround to that weird behavior

--- 
### basic stuff to install
- bspwm (duh)
- xfce4 (desktop environment)
- picom (EYE CANDY 🤑🤑🤑🤑)
- kitty (terminal)

#### other things in screenshots:
- fastfetch
  - hyfetch for the gays
- fish
- qimgv
- cava
- cmatrix
- rmpc
- btop
---
### nerd fonts used:
- Ubuntu Mono (proportional/normal font)
- JetbrainsMono (monospace/terminal font)

  https://www.nerdfonts.com/font-downloads

### gtk/qt theme:
- https://github.com/vinceliuice/vimix-gtk-themes
- https://github.com/vinceliuice/vimix-kde
-----
### notes:

1. `xfce4-session-settings` is primarily used for managing startup programs with the xfce session
