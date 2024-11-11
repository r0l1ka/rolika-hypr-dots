<div align="right">

<h2>Script</h2>

</div>

```
git clone https://github.com/r0l1ka/rolika-hypr-dots/blob/main/script/1%20-%20dependencies
./1\ \-\dependencies
```

See [script](https://github.com/r0l1ka/rolika-hypr-dots/tree/main/script)


<div align="right">

<h2>Manual (not recommended)</h2>

</div>

**1.** Install dependencies | Arch (pacman + yay)
```
sudo pacman -S hyprland kitty chromium spotify nautilus swaync wlogout hyprshot hyprpicker
yay -S latr
```

**2.** Download [dots](https://github.com/r0l1ka/rolika-hypr-dots/releases/download/Alpha/v.dots.zip) and put to ~
```
git clone https://github.com/r0l1ka/rolika-hypr-dots/releases/download/Alpha/v.dots.zip; cd v.dots
cp -r .config ~; cp -r .icons ~; cp -r Wallpapers ~
cd ..; rm -r v.dots  # !! Dont copy this line if you want have copy of config !!
```

**3.** Go to `~/.config` and set up it manually
