# Dotfiles
Install the following and add the necessary dotfiles to your home folder.
you can omit the fonts, themes and icons files if you want to configure it yourself 

(the fonts dotfile may be deleted as its too large)
```
i3-lock
i3 (build from github for the latest version with integrated i3-gaps)
picom
kitty
nvchad
bumblebee-status (build from github)
bash4.sh (install from github) for the gif background
rofi
oh-my-zsh
powerlevel10k zsh
zsh (obviously)
thunar
maim
xclip
xdotool
xss-lock
fontawesome
saucecodepro nf
jetbrains nf
```

Install catppuchin firefox theme


## what you can expect:
1. catppuchin gtk theme
2. minimal i3 configuration, remapped just mod+shift+q to mod+q + bunch of other shortcuts added
3. mod shift x to lock, mod shift g to set gif as background, icons for workspaces, firefox opens in 2, chroms in 3 (benefit: keep chrome as default browsers so when you open pythonserver links they go to the third workspace instead of the second where you can use firefox for documentation), file managers, nautilus and thunar at ws 4 and obs at ws5. 
4. fibonacchi i3
6. i3 gaps with catppuchin highlights
7. kitty terminal with nerd fonts and minimal changes
8. background blur using picom on terminal, nautilus and thunar
9. bumblebee status bar containing battery, brightness, cpu usage, memory usage, and datetime on the solarized dark theme

## Caveats:
In order to stop the gif background, run
```
killall bash
```
and restart i3 with `mod+shift+r`

# Preview

Please preview from google drive: https://drive.google.com/file/d/1LmtA5c16x6XUgmn6wmJjKtBPtrgvlh78/view?usp=sharing
