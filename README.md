<div align="center">
<h1>v/dots | A-0.3</h1>
<h3>or violet/hypr dots.</h3>
</div>

![image](https://github.com/user-attachments/assets/dfc096c0-5ad3-4068-8c8d-8f78da19c17c)

<div align="center">
<h3>Based on <img height="14" width="14" src="https://avatars.githubusercontent.com/u/107882187?s=200&v=4" /> <a href="https://hyprland.org/">Hyprland</a>, an independent tiling <a href="https://wayland.freedesktop.org/">Wayland</a> compositor written in C++.</h3>
</div>

****************************

<h1>Apps used</h1>

<div align="center">

| Purpose | App | - | Pre-installed | App |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Bar | <img height="14" width="14" src="https://avatars.githubusercontent.com/u/146791241?s=200&v=4" /> [Fabric](https://github.com/Fabric-Development/fabric) |  | Terminal |  <img height="14" width="14" src="https://upload.wikimedia.org/wikipedia/commons/2/2f/Kitty%28Terminal-emulator%29.png" /> [kitty](https://github.com/kovidgoyal/kitty) |
| Notif. center | <img height="14" width="14" src="https://cdn.simpleicons.org/linux/black" /> [SwayNC](https://github.com/ErikReider/SwayNotificationCenter) |  | Browser | <img height="14" width="14" src="https://www.chromium.org/_assets/icon-chromium-96.png" /> [Chromium](https://www.chromium.org/getting-involved/download-chromium/)  |
| Clipboard MGR | <img height="14" width="14" src="https://cdn.simpleicons.org/linux/black" /> [Clipse](https://github.com/savedra1/clipse) |  | File MGR | <img height="14" width="14" src="https://apps.gnome.org/icons/scalable/org.gnome.Nautilus.svg" /> [Nautilus](https://apps.gnome.org/en/Nautilus/) |
| Screenshot MGR | <img height="14" width="14" src="https://avatars.githubusercontent.com/u/107882187?s=200&v=4" /> [Hyprshot](https://github.com/Gustash/Hyprshot) | | Online Music MGR | <img height="14" width="14" src="https://upload.wikimedia.org/wikipedia/commons/7/75/Spotify_icon.png" /> [Spotify](https://spotify.com) +  [Spicitefy](https://spicetify.app) |
| Color picker | <img height="14" width="14" src="https://avatars.githubusercontent.com/u/107882187?s=200&v=4" /> [Hyprpicker](https://github.com/hyprwm/hyprpicker) |  | Text / Code Editor | <img height="14" width="14" src="https://upload.wikimedia.org/wikipedia/commons/0/07/Neovim-mark-flat.svg" /> [Neovim](https://neovim.io) + [Neovide](https://neovide.dev) |
| Power MGR | <img height="14" width="14" src="https://cdn.simpleicons.org/linux/black" /> [WLogout](https://github.com/ArtsyMacaw/wlogout)  |  |  |  |
| Pie-Menu | <img height="14" width="14" src="https://avatars.githubusercontent.com/u/130886533?s=200&v=4" /> [Kando](https://github.com/kando-menu/kando) |  |  |  |  |

</div>

**You can change pre-installed apps in config**


<div>
<h1>Download + Install</h1>
</div>

**IN ALPHA. not done yet**

**Recommend use newly installed arch**



<div align="right">

<h2>Script</h2>

</div>

```
No auto download + set and install script for now.
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



<h1>Preview</h1>
<details> 
  <summary>Photos</summary>



</details>

<details> 
  <summary>Videos</summary>



</details>

<h1>To-do list</h1>

**Will be done in release**
+ **Bar**
+ **Openable sidebar (with Fabric)** | Concept design >

<details> 
  <summary>Photos</summary>

![hypr sidebar@1x](https://github.com/user-attachments/assets/566ec93e-97e2-4f91-9edb-aa0f25ca8c4a)
![hypr sidebar copy@1x](https://github.com/user-attachments/assets/7c424335-4981-4002-95c7-55adb3fb4043)
![hypr sidebar copy 3@1x](https://github.com/user-attachments/assets/4e53aad3-19ab-4029-b340-6a89787469e5)
![hypr sidebar copy 2@1x](https://github.com/user-attachments/assets/848e3485-948b-4ee8-858f-1df9dd58defd)
![hypr sidebar (Sound)@1x](https://github.com/user-attachments/assets/47262711-aefe-4f1b-ad75-6aac946c26c3)
![hypr sidebar (Open'd Apps Collapse)@1x](https://github.com/user-attachments/assets/7575e55d-ad3e-4b95-b355-06b43aa0c3cf)
![hypr sidebar (Internet - Wi-Fi)@1x](https://github.com/user-attachments/assets/5b2ce7b0-8a29-42ab-ae9d-1d8ae6371ff3)
![hypr sidebar (Internet - Wi-Fi) Copy@1x](https://github.com/user-attachments/assets/4103a206-a641-4787-8faa-3fe38b663f53)
![hypr sidebar (Internet - Wi-Fi) Copy 2@1x](https://github.com/user-attachments/assets/612f692e-f135-420a-8c6d-0a4adf921eba)
![hypr sidebar (Bluetooth)@1x](https://github.com/user-attachments/assets/4a524289-5903-4b36-98c4-7c4f826e4419)

</details>

+ **rofi config**

<h1>Other</h1>

<div align="center">
  
[About config](https://github.com/r0l1ka/rolika-hypr-dots/blob/main/visual/aboutconfig.md) | [About author](https://t.me/rolika_bio)

</div>
