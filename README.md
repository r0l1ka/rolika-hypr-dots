<div align="center">
<h1>v/dots | A-0.3</h1>
<h3>or violet/hypr dots.</h3>
</div>

![image](https://github.com/user-attachments/assets/dfc096c0-5ad3-4068-8c8d-8f78da19c17c)

<div align="center">
<h3>Based on <img height="14" width="14" src="https://avatars.githubusercontent.com/u/107882187?s=200&v=4" /> <a href="https://hyprland.org/">Hyprland</a>, an independent tiling <a href="https://wayland.freedesktop.org/">Wayland</a> compositor written in C++.</h3>
</div>

****************************

<h1>App used</h1>

<div style="display: flex; justify-content: space-between;">
  <table style="width: 45%;">
    <tr>
      <th>Purpose</th>
      <th>App</th>
    </tr>
    <tr>
      <td>Bar</td>
      <td><img height="14" width="14" src="https://avatars.githubusercontent.com/u/146791241?s=200&v=4" /> <a href="https://github.com/Fabric-Development/fabric">Fabric</a></td>
    </tr>
    <tr>
      <td>Notif. center</td>
      <td><img height="14" width="14" src="https://cdn.simpleicons.org/linux/black" /> <a href="https://github.com/ErikReider/SwayNotificationCenter">SwayNC</a></td>
    </tr>
    <tr>
      <td>Clipboard MGR</td>
      <td><img height="14" width="14" src="https://cdn.simpleicons.org/linux/black" /> <a href="https://github.com/savedra1/clipse">Clipse</a></td>
    </tr>
    <tr>
      <td>Screenshot MGR</td>
      <td><img height="14" width="14" src="https://avatars.githubusercontent.com/u/107882187?s=200&v=4" /> <a href="https://github.com/Gustash/Hyprshot">Hyprshot</a></td>
    </tr>
    <tr>
      <td>Color picker</td>
      <td><img height="14" width="14" src="https://avatars.githubusercontent.com/u/107882187?s=200&v=4" /> <a href="https://github.com/hyprwm/hyprpicker">Hyprpicker</a></td>
    </tr>
    <tr>
      <td>Power MGR</td>
      <td><img height="14" width="14" src="https://cdn.simpleicons.org/linux/black" /> <a href="https://github.com/ArtsyMacaw/wlogout">WLogout</a></td>
    </tr>
    <tr>
      <td>Pie-Menu</td>
      <td><img height="14" width="14" src="https://avatars.githubusercontent.com/u/130886533?s=200&v=4" /> <a href="https://github.com/kando-menu/kando">Kando</a></td>
    </tr>
  </table>

  <table style="width: 45%;">
    <tr>
      <th>Pre-installed</th>
      <th>App</th>
    </tr>
    <tr>
      <td>Terminal</td>
      <td><img height="14" width="14" src="https://upload.wikimedia.org/wikipedia/commons/2/2f/Kitty%28Terminal-emulator%29.png" /> <a href="https://github.com/kovidgoyal/kitty">kitty</a></td>
    </tr>
    <tr>
      <td>Browser</td>
      <td><img height="14" width="14" src="https://www.chromium.org/_assets/icon-chromium-96.png" /> <a href="https://www.chromium.org/getting-involved/download-chromium/">Chromium</a></td>
    </tr>
    <tr>
      <td>File MGR</td>
      <td><img height="14" width="14" src="https://apps.gnome.org/icons/scalable/org.gnome.Nautilus.svg" /> <a href="https://apps.gnome.org/en/Nautilus/">Nautilus</a></td>
    </tr>
    <tr>
      <td>Online Music MGR</td>
      <td><img height="14" width="14" src="https://upload.wikimedia.org/wikipedia/commons/7/75/Spotify_icon.png" /> <a href="https://spotify.com">Spotify</a> + <a href="https://spicetify.app">Spicetify</a></td>
    </tr>
    <tr>
      <td>Text / Code Editor</td>
      <td><img height="14" width="14" src="https://upload.wikimedia.org/wikipedia/commons/0/07/Neovim-mark-flat.svg" /> <a href="https://neovim.io">Neovim</a> + <a href="https://neovide.dev">Neovide</a></td>
    </tr>
	    <tr><td></td>
      <td>
    </tr>
	    <tr>
      <td><img></td>
      <td></td>
    </tr>
  </table>
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
