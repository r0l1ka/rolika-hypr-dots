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

<div align="center">

| **Purpose** | **App** |
|:---|:---|
| Terminal |  <img height="14" width="14" src="https://upload.wikimedia.org/wikipedia/commons/2/2f/Kitty%28Terminal-emulator%29.png" /> [kitty](https://github.com/kovidgoyal/kitty) |
| Bar | <img height="14" width="14" src="https://avatars.githubusercontent.com/u/146791241?s=200&v=4" /> [Fabric](https://github.com/Fabric-Development/fabric)
| Browser | <img height="14" width="14" src="https://www.chromium.org/_assets/icon-chromium-96.png" /> [Chromium](https://www.chromium.org/getting-involved/download-chromium/) 
| Wallp. MGR | <img height="14" width="14" src="https://cdn.simpleicons.org/linux/black" /> [swww](https://github.com/LGFae/swww) |
| File MGR | <img height="14" width="14" src="https://apps.gnome.org/icons/scalable/org.gnome.Nautilus.svg" /> [Nautilus](https://apps.gnome.org/en/Nautilus/) |
| Online Music MGR | <img height="14" width="14" src="https://upload.wikimedia.org/wikipedia/commons/7/75/Spotify_icon.png" /> [Spotify](https://spotify.com) +  [Spicitefy](https://spicetify.app) |
| Notif. center | <img height="14" width="14" src="https://cdn.simpleicons.org/linux/black" /> [SwayNC](https://github.com/ErikReider/SwayNotificationCenter) |
| Screenshot MGR | <img height="14" width="14" src="https://avatars.githubusercontent.com/u/107882187?s=200&v=4" /> [Hyprshot](https://github.com/Gustash/Hyprshot) |
| Color picker | <img height="14" width="14" src="https://avatars.githubusercontent.com/u/107882187?s=200&v=4" /> [Hyprpicker](https://github.com/hyprwm/hyprpicker) |
| Power MGR | <img height="14" width="14" src="https://cdn.simpleicons.org/linux/black" /> [WLogout](https://github.com/ArtsyMacaw/wlogout) |
| Pie-Menu | <img height="14" width="14" src="https://avatars.githubusercontent.com/u/130886533?s=200&v=4" /> [Kando](https://github.com/kando-menu/kando) |

</div>



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

    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Fluorum</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <div class="ml-auto">
					<a class="btn btn-link btn-support" href="https://discord.gg/bTgtdW78">Support</a>
                    <button class="btn btn-outline-light btn-buy" onclick="showNotification()">Use now!</button>        
                </div>
            </div>
        </div>
    </nav>

    <!-- Menu Section -->
    <section class="menu">
        <div class="content">
            <h1>Fluorum</h1>
            <p>Provides you with simplification of the game</p>
            <button class="btn btn-outline-light btn-script" onclick="showNotification()">Use now!</button>
        </div>
    </section>

    <!-- Advantages Section -->
    <div class="advantages-section">
        <h2 class="section-title">Our Advantages</h2>
        <div class="advantages-container">
            <div class="advantage-item">
                <i class="fas fa-rocket fa-3x mb-3"></i> <!-- Adding an icon -->
                <h4>Speed</h4>
                <p>Lightning-fast performance of our services for your convenience.</p>
            </div>
            <div class="advantage-item">
                <i class="fas fa-shield-alt fa-3x mb-3"></i> <!-- Icon -->
                <h4>Security</h4>
                <p>Your data is securely protected by advanced encryption technologies.</p>
            </div>
            <div class="advantage-item">
                <i class="fas fa-users fa-3x mb-3"></i> <!-- Icon -->
                <h4>Support</h4>
                <p>Our support team is available 24/7 to assist you with any questions.</p>
            </div>
        </div>
    </div>

    <!-- FAQ Section -->
    <div class="faq-section">
        <h2 class="section-title">Frequently Asked Questions</h2>
        <div class="faq-container">
            <div class="faq-item">
                <div class="faq-question">
                    <span>How does our service work?</span>
                    <i class="fas fa-chevron-down arrow-icon"></i>
                </div>
                <div class="faq-answer">
                    <p>Our service provides fast and secure solutions for data processing with a high level of protection.</p>
                </div>
            </div>
            <div class="faq-item">
                <div class="faq-question">
                    <span>What data is protected?</span>
                    <i class="fas fa-chevron-down arrow-icon"></i>
                </div>
                <div class="faq-answer">
                    <p>All client data, including personal information and financial transactions, is securely protected.</p>
                </div>
            </div>
            <div class="faq-item">
                <div class="faq-question">
                    <span>Is there technical support?</span>
                    <i class="fas fa-chevron-down arrow-icon"></i>
                </div>
                <div class="faq-answer">
                    <p>Yes, our support team is available 24/7 to resolve any of your issues.</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <div class="footer-description">Fluorum</div>
        <div class="footer-copyright">Copyright &copy; Fluorum</div>
        <nav class="footer-nav">
            <a href="#home">Home</a>
            <a href="https://discord.gg/bTgtdW78">Support</a>
        </nav>
    </footer>

	<script src="https://cdn.jsdelivr.net/npm/notyf@3/notyf.min.js"></script>
    	<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    	<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js"></script>
    	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
	<script src="script.js"></script>
