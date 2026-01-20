# ZestyTheme

A minimal and elegant theme for Jellyfin based on/inspired by [Ultrachromic](https://github.com/CTalvio/Ultrachromic), [Glassmorphism](https://github.com/alexyle/jellyfin-theme), [Scyfin](https://g...)

**Now with two login wallpaper options: minimal and stylish!**<br>
Compatible with 10.11+ & Tablets!

---

### **Screenshots:**

<img src="./images/home.jpg" alt="home" width="100%"/>
<img src="./images/nice-guys.jpg" alt="movies" width="100%"/>
<img src="./images/avatar.jpg" alt="tv-shows" width="100%"/>
<img src="./images/player.jpg" alt="player" width="100%"/>

Two login wallpaper options: Minimal and Stylish.

<img src="./images/login.jpg" alt="login" width="100%"/>

**Mobile:**

<img src="./images/phone.jpg" alt="phone" width="100%"/>

---

## Installing

To add the theme to Jellyfin `v10.11+`, copy the following line to Dashboard > Branding² > Custom CSS:

```
@import url('https://cdn.jsdelivr.net/gh/djmohsen/dmTheme@latest/theme.css');
```

<br>

<details>
<summary>For older Jellyfin versions (v10.10), add the following line instead:</summary>

Jellyfin `v10.10.x`:
<br>
```
@import url('https://cdn.jsdelivr.net/gh/djmohsen/dmTheme@legacy/v10.10/theme.css');
```
</details>

Then, if you haven't already, enable Backdrops for _every_ device using this theme (Settings > Display > Backdrops).¹

## Color schemes

Add **one** of the following @import lines _if_ you'd like to change the default colors to one of the presets below (optional):

### Cyan
<img src="./images/colorschemes/cyan.png" alt="default" width="30%"/>

The default color scheme.

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-cyan.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/cyan.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Blue

<img src="./images/colorschemes/blue.png" alt="blue" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/djmohsen/dmTheme@latest/colorschemes/blue.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-blue.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/blue.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Coral

<img src="./images/colorschemes/coral.png" alt="coral" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/djmohsen/dmTheme@latest/colorschemes/coral.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-coral.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/coral.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Gray

<img src="./images/colorschemes/gray.png" alt="gray" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/djmohsen/dmTheme@latest/colorschemes/gray.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-gray.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/gray.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Green

<img src="./images/colorschemes/green.png" alt="green" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/djmohsen/dmTheme@latest/colorschemes/green.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-green.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/green.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Purple

<img src="./images/colorschemes/purple.png" alt="purple" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/djmohsen/dmTheme@latest/colorschemes/purple.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-purple.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/purple.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Red

<img src="./images/colorschemes/red.png" alt="red" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/djmohsen/dmTheme@latest/colorschemes/red.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-red.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/red.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Yellow

<img src="./images/colorschemes/yellow.png" alt="yellow" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/djmohsen/dmTheme@latest/colorschemes/yellow.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-yellow.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/yellow.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>
<br>

For more info on custom colors [click here](./colorschemes/COLORS.md). For more color schemes check out MakD's [Zombie Repo](https://github.com/MakD/zombie-release/tree/main#color-palettes).

### Alt login wallpaper
Finally, _if_ you would like to use the alternative(stylish) login wallpaper, add the line below to your Custom CSS as well:

```css
@import url('https://cdn.jsdelivr.net/gh/djmohsen/dmTheme@latest/login-alt.css');
```

This is a comparison between the minimal(default) and stylish versions of the login wallpaper:

<details>
 <summary>Blue</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-blue.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-blue.jpg" alt="default" width="100%"/>
 </div>
</details>

... (rest of README unchanged)