
<h1 align="center">
  <br>
  <a href="https://github.com/tmcybers/Spanner-Hacken-Custom-Project"><img src="spannerlogo.png" width="500px" alt="gmailHack"></a>
</h1>

<h4 align="center">☣️ Spanner Hacken Machine ☣️</h4>

---

<p align="center">
<a href="https://github.com/tmcybers/Spanner-Hacken-Custom-Project"><img src="https://img.shields.io/badge/XML-yellowgreen">
<a href="https://github.com/tmcybers/Spanner-Hacken-Custom-Project"><img src="https://img.shields.io/badge/downloads-36734-green">
<a href="https://github.com/tmcybers/Spanner-Hacken-Custom-Project"><img src="https://img.shields.io/badge/releases-1.0-red">
<a href="https://github.com/tmcybers/Spanner-Hacken-Custom-Project"><img src="https://img.shields.io/badge/contributors-1-orange">
<a href="https://github.com/tmcybers/Spanner-Hacken-Custom-Project/"><img src="https://img.shields.io/badge/open%20issues-0-blue">
<a href="https://github.com/tmcybers/Spanner-Hacken-Custom-Project"><img src="https://img.shields.io/badge/discussions-1-orange">
<a href="https://t.me/+l5WYQySOL-0yMDQ0"><img src="https://img.shields.io/badge/chat-online-brightgreen?style=plastic&logo=telegram">
<a href="https://twitter.com/tmcybers"><img src="https://img.shields.io/badge/folow-tmcyber-blue?style=plastic&logo=twitter">
<a href="https://ioc.exchange/@tmcyber"><img src="https://img.shields.io/badge/folow-tmcyber-blue?style=plastic&logo=mastodon">
<a href="https://tmcybers.github.io/blog"><img src="https://img.shields.io/badge/Write%20ups-Blog-red?style=plastic&logo=hackthebox">
  <a href="https://wakatime.com/@tmcyber"><img src="https://img.shields.io/badge/Developer-Blog-orange?style=plastic&logo=python">
<a href="https://tmcybers.github.io/Donate"><img src="https://img.shields.io/badge/support-tmcyber-blue?style=plastic&logo=donate">
<a href="https://ko-fi.com/tmcyber"><img src="https://img.shields.io/badge/Support%20me-Ko--Fi-brightgreen?style=plastic&logo=ko-fi">

</p>
  
---
![2023-03-01_12-31](https://user-images.githubusercontent.com/97669969/222127630-ce5bda78-0b41-4f32-8edc-d677e2b7a5d8.png)
---

# ⚒️ My||Hacking||Environment|||Openbox||Based ⚒️


# Important for You #

  `This repo is in Constant Development and Updates`

  `Future changes will be applied both to Appearance/Custom and to further /Automate the Hacking and Development work, will include tools and scripts for:`
  ```
  * targets/
  * dirs/
  * reports/
  * binary/
  * reversing/
  * malware/
  * threathunting/
  * investigation tools/
  * osint/
  * checking reputation/
  * sandboxs/
  * vunlerabilty DBS/
  * cheat sheets/
  
  * and more, stay ⚔️ Hacken ⚔️!
 ```


* 🗿 My custom of what y use every day for 💉 hacking and threat hunting 🔫 is based on Debian/Parrot Os ↪️ Openbox tilling window*

↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️`Why openbox`↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️↘️

### 🕶️ Openbox is the most lightweight tilling window [openbox offers you the freedom 🕶️ to work with shortcuts or mouse, your choice is your choice 🏆

  
              ☢️ Never automate these types of customs they are easily broken according to dependencies and system requirements ☢️
  
  
  
  ## ⚒️ Instalation proceed ⚒️
```
sudo apt update
sudo parrot-upgrade
sudo apt install openbox
sudo apt install obconf lxinput
sudo apt install snapd (snap discontinued)
sudo apt install mpd
sudo apt install flameshot
sudo apt install fonts-material-design-icons-iconfont
sudo apt install fonts-materialdesignicons-webfont

```

## 📑 Fonts 📑 [very important]
  
1.) Download some [Nerd Fonts](https://www.nerdfonts.com/)

2.) We need the fonts to be available system-wide, you'll need to copy them to `/usr/local/share/fonts` and reboot / or manually rebuild the font cache with `fc-cache -fv`

3.) Run the command `fc-cache -fv` to manually rebuild the font cache.

 * Is very important to have Iosevka Nerd Font or Hack Nerd Font this are polybar dependencies, after that choose a font as your liking.
  
 ## 🗿 Wallpaper manager 🗿
  
```
sudo apt install nitrogen
```
  
## Manager for Menu/Custom Themes and Icons
  
```
sudo apt install lxappearance lxappearance-obconf
```
  
## Wallpapers for  Hacken Machine [Nitrogen]

[Hacken Machine Nord Pallete Wallpapers ☬ NoRD Pallete ßÿ тм¢увєя ☬](https://github.com/tmcybers/Hacken-Machine-Nord-Pallete-Wallpapers)
  
  
# Important Step! we are going to create the `autostart` , so that everything starts at startup.

---

##### If just in case some of the directories you have, then go to the next level.
  
```
cd /home/tmcyber/.config
mkdir openbox
cd openbox
touch autostart 
geany autostart
```
### Example, will add more later.
  
```
# Launch nitrogen
nitrogen --restore &

# Set keyboard to ES or US
setxkbmap us
  
#Launch Picom
picom &
  
## Launch Polybar 
bash ~/.config/polybar/launch.sh --forest 
```
* `In this folder you must also find the rc.xml file, which is the shortcuts file that we are going to tune with our personal shortcuts later on`

*This # is a comment, into autostart*

### Rofi Launcher

```
sudo apt install rofi
```

#### Ok now restart, you can do it simply like this `kill -9 -1` now everything is black don't be scared, don't worry open a terminal with the right click terminal emulater, type nitrogen and upload to nitrogen the wallapers that you downloaded `the pallete nord`from this repo or others as your choice.

  
## 💊 Polybar TUN!!nG! 💊
  
[Polybar-themes](https://github.com/adi1090x/polybar-themes)
 
```
git clone --depth=1 https://github.com/adi1090x/polybar-themes.git
cd polybar-themes
chmod +x setup.sh
  
```
  
### Run setup.sh and select a style
  
``` 
./setup.sh
```
  
```
[*] Installing Polybar Themes...

[*] Choose Style -
[1] Simple
[2] Bitmap

[?] Select Option : 1

[*] Installing fonts...
[*] Creating a backup of your polybar configs...
[*] Successfully Installed.
```
### Launch the bar
*To launch the bar with the selected theme, Just...*

Open the terminal and enter the following command

```
bash ~/.config/polybar/launch.sh
```

### Usage : launch.sh --theme

Available Themes :
--blocks    --colorblocks    --cuts      --docky
--forest    --grayblocks     --hack      --material
--panels    --pwidgets       --shades    --shapes

### Now, select your theme and launch the bar
  
```
bash ~/.config/polybar/launch.sh --hack
```
  
#### Im using --forest as theme
  
**Paste this comand into `autostart` that we have create at the start.
  
 
## 💊 Kitty TUN!!nG! 💊

[kitty-themes](https://github.com/dexpota/kitty-themes)
  
**In case that you don't see this / simply create then***
  
```
cd
cd .config
cd kitty
touch kitty.conf
geany kitty.conf
```
  
* paste this into kitty.conf 
  
``` 
include myconf.conf
```
  
```
touch myconf.conf
```

* Cool, now go and choose a theme from dexpotas repo and just paste it into myconf.conf
   
  
* Im using DotGov as theme and Atom also, i switch every time i change my wallpapers from nord pallete (https://github.com/tmcybers/Hacken-Machine-Nord-Pallete-Wallpapers)

**Atom theme** (https://github.com/dexpota/kitty-themes/blob/master/themes/Atom.conf)

```background            #161718
background_opacity    0.9
foreground            #c4c8c5
cursor                #d0d0d0
selection_background  #444444
color0                #000000
color8                #000000
color1                #fc5ef0
color9                #fc5ef0
color2                #86c38a
color10               #94f936
color3                #ffd6b1
color11               #f5ffa7
color4                #85befd
color12               #95cbfe
color5                #b9b5fc
color13               #b9b5fc
color6                #85befd
color14               #85befd
color7                #dfdfdf
color15               #dfdfdf
selection_foreground #161718
```
* I had opacity set  to 0.9 set it to your tasteª.
  
  * Kitty shortcuts here: (https://sw.kovidgoyal.net/kitty/overview/)

#### 🏹 Zsh || Powerlevel10k for kitty 🏹
  

**Installl zsh**
  
 ```
sudo apt-get install zsh
```

**Put ZSH as default shell**
  
```
chsh -s $(which zsh)
```

**We close and reopen the terminal to verify that ZSH is the default (sometimes the system may have to be restarted)**
  
```
❯ echo $SHELL
  
/usr/bin/zsh
```

#### OH-MY-ZSH

*We execute the following command to download and install oh-my-zsh*
  
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" 
```
  
*Once installed we access the oh-my-zsh configuration*
  
```
geany ~/.zshrc
```

*A document will open that we must edit by adding the following line*
  
```
ZSH_THEME="powerlevel10k/powerlevel10k"
```

* In this case we add: ZSH_THEME=”powerlevel10k/powerlevel10k”

More themes available for oh-my-zsh in the following link [ohmyzsh-themes](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes)


#### 🩸 POWERLEVEL10K 🩸
  
**To install powerlevel10k we must execute the following command**
  
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k 
```

**Once we execute it, we close the terminal and open it again and follow the configuration steps that we like the most**

### [!] The installation and configuration has to be done twice, for the user without permissions and for the root user.

#### Plugins

[plugins-list](https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins)

> zsh-syntax-highlighting (It checks which commands are well written or if they exist and also which ones are misspelled or do not exist)
  
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
``` 

> zsh-autosuggestions (View suggestions and predict the tasks you want to perform based on the most used commands)
  
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

**Paste this into ~/.zhsrc**
  
```
  geany ~/.zshrc
  
```
  
```
  
plugins=(git
zsh-syntax-highlighting
zsh-autosuggestions
)
  
```
  
  
## 🔱 Picom transparency TUN!!nG! 🔱

```
cd .config
mkdir picom
touch picom.conf
geany picom.conf
```
* Into picom.conf just paste my conf, and modelling to your liking.
  
* Sample here:
[picom sample](https://github.com/yshui/picom/blob/next/picom.sample.conf)

# Update 2023

**I only use `background_opacity 0.9` in Kitty. Picom is Disabled**
  
  
## 💻 Mosaic Windows Tilling [CTRL+1,2,3,4,45,5,6,7,8,9] 💻
 
* Open rc.xml , and just paste this code, save it, and then do right click and ReConfigure openbox.
  
 ```

<keybind key="C-1">
  <action name="UnmaximizeFull"/>
  <action name="MoveResizeTo">
    <x>0</x>
    <y>-0</y>
    <width>50%</width>
    <height>50%</height>
  </action>
</keybind>
    <keybind key="C-2">
      <action name="UnmaximizeFull"/>
      <action name="MoveResizeTo">
        <x>0</x>
        <y>-0</y>
        <width>100%</width>
        <height>50%</height>
      </action>
    </keybind>
    <keybind key="C-3">
      <action name="UnmaximizeFull"/>
      <action name="MoveResizeTo">
        <x>-0</x>
        <y>-0</y>
        <width>50%</width>
        <height>50%</height>
      </action>
    </keybind>
    <keybind key="C-4">
      <action name="UnmaximizeFull"/>
      <action name="MoveResizeTo">
        <x>0</x>
        <y>0</y>
        <width>50%</width>
        <height>100%</height>
      </action>
    </keybind>
    <keybind key="C-5">
      <action name="MaximizeFull"/>
    </keybind>
    <keybind key="C-6">
      <action name="UnmaximizeFull"/>
      <action name="MoveResizeTo">
        <x>-0</x>
        <y>0</y>
        <width>50%</width>
        <height>100%</height>
      </action>
    </keybind>
    <keybind key="C-7">
      <action name="UnmaximizeFull"/>
      <action name="MoveResizeTo">
        <x>0</x>
        <y>0</y>
        <width>50%</width>
        <height>50%</height>
      </action>
    </keybind>
    <keybind key="C-8">
      <action name="UnmaximizeFull"/>
      <action name="MoveResizeTo">
        <x>0</x>
        <y>0</y>
        <width>100%</width>
        <height>50%</height>
      </action>
    </keybind>
    <keybind key="C-9">
      <action name="UnmaximizeFull"/>
      <action name="MoveResizeTo">
        <x>-0</x>
        <y>0</y>
        <width>50%</width>
        <height>50%</height>
      </action>
    </keybind>
    <keybind key="W-Right">
      <action name="UnmaximizeFull"/>
      <action name="MaximizeVert"/>
      <action name="MoveResizeTo">
        <width>50%</width>
      </action>
      <action name="MoveToEdgeEast"/>
    </keybind>
    <keybind key="W-Left">
      <action name="UnmaximizeFull"/>
      <action name="MaximizeVert"/>
      <action name="MoveResizeTo">
        <width>50%</width>
      </action>
      <action name="MoveToEdgeWest"/>
    </keybind>
    <keybind key="W-Up">
      <action name="MaximizeFull"/>
    </keybind>
    <keybind key="W-Down">
      <action name="UnmaximizeFull"/>
      <action name="MoveResizeTo">
        <width>80%</width>
        <height>80%</height>
      </action>
      <action name="MoveToCenter"/>
    </keybind>

```
> Open some window or terminal and try it.
## How does this work? 
>>> Hold down the super key or Win key in windows is usually called like this, and with the right and left arrows play with the window to your liking
  

  
##  🕶️ Custom Shortcuts 🕶️
  
* rc.xml
  
* Example 📖
  
```
     <keybind key="W-t">
      <action name="Execute">
        <command>kitty</command>
      </action>
    </keybind>
```
* Im saying to openbox that i will open kitty with Superkey/Winkey Windows and  key t [ custom as your choice]
    
* Im using custom shortcuts to open every applicaccion, and tilling it.
    
 #### For the Flameshot shortcut Is Having an issue. But calling `flameshot gui` like this, as <command> it shows.  

 * Flameshot 📗 is the best tool for reports/write ups 📗  
    
    
    
# 🎨 Shell TUN!!nG!+Extra! 🎨

**Lsd**
    
* Ubuntu/Debian based distro
    
```
use sudo dpkg -i lsd_0.23.1_amd64.deb and get .deb file from release page 
```
    
[lsd releases](https://github.com/Peltoche/lsd/releases/)
    
![2023-03-05_20-35](https://user-images.githubusercontent.com/97669969/222982461-55c12de7-5da5-4456-bda5-f11ae05c0e67.png)


**batcat**
    
```
sudo apt install bat   
```
 
![2023-03-05_20-55](https://user-images.githubusercontent.com/97669969/222982692-bfdd1ef5-df0c-4bab-b348-55e92efb28eb.png)

 
# 💎 Opcional Things for TUN!!nG! 💎
    
# Conky 

![conky_hacken](https://user-images.githubusercontent.com/97669969/226741424-bd438e23-6ba1-47ce-a485-1e5dc6ab6e88.png)

* Conky Hacken is Released (https://github.com/tmcybers/Conky-Hacken)

#### Optional [Conky Themes]

[conky-themes](https://github.com/addy-dclxvi/conky-theme-collections)

**Start conky on startup echo this into `autostart`**
    
```
conky &
    
```
    

### Panel tint2

`Some dependencies in case you miss something`
    
```
sudo apt-get install libcairo2-dev libpango1.0-dev libglib2.0-dev libimlib2-dev libgtk-3-dev libxinerama-dev libx11-dev libxdamage-dev libxcomposite-dev libxrender-dev libxrandr-dev librsvg2-dev libstartup-notification0-dev
```
    
```
sudo apt install tint2
```
    
**Start tint2 on startup echo this/into `autostart`
    
```
tint2 &
    
```
* tint2 is the lightest bar that there is / is more lightwey than polybar and 100% customizable. [Your choice is all up to you]

# Best Themes for tint2

* Create a directory inside in your home folder
    
```
~/.config
```

```
mkdir -p ~/.config/tint2
```
    
Then just clone the repository, which I separated all previously, and move to ~/.config/tint2/
    
```
git clone https://github.com/terroo/tint2-themes
cd tint2-themes
mv * ~/.config/tint2/
```

To test use the tint2 command with the -c parameter and the path of the Tint2 configuration file(tint2rc), example:
    
```
tint2 -c ~/.config/tint2/livia/livia.tint2rc
```

If you want to enable(make your life easier!) for every time you log into Openbox, add to your `~/.config/openbox/autostart` the line:
    
```
tint2 -c ~/.config/tint2/livia/livia.tint2rc 
```
 
* Im using polybar now-days, but i have used tint2 because consumes very few resources[less than polybar] / so your choice is fully your.
    
 
    ---
  
  

<h4 align="center">⌨️ Shortcuts (Some of it) ⌨️</h4>

     ⌨️ Aplicaccion shortcuts launchers ⌨️
    
   * (W) Super-key/Win-key + t = kitty
   * (W) Super-key/Win-key + p = brave browser
   * (W) Super-key/Win-key + o = caja
   * (W) Super-key/Win-key + i = flameshot
   * (W) Super-key/Win-key + u = geany
   * (W) Super-key/Win-key + y = vscode
    
    ⌨️ System Launcher ⌨️
    
   * (W) Super-key/Win-key + m = rofi
   * (W) Super-key/Win-key + n = rofi show window
   * (W) Super-key/Win-key + b = rofi-ssh
    
    ⌨️ Desktops ⌨️
    
   * (W) Super-key/Win-key + 1 = Desktop 1
   * (W) Super-key/Win-key + 2 = Desktop 2
   * (W) Super-key/Win-key + 3 = Desktop 3
   * (W) Super-key/Win-key + 4 = Desktop 4
    
    ⌨️ Window Tilling ⌨️
    
   * (W) Super-key/Win-key + ➡️ = till windows to right
   * (W) Super-key/Win-key + ⬅️ = till window to left
   * (W) Super-key/Win-key + ↗️ = till to bellow boottom dektop aslo full screen of the window
   * (W) Super-key/Win-key + ↘️ = till to down of the desktop (floating window)
    
    *rc.xml is the shortcut/master of all unity system
---
    
    
    





[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Courier+new&color=%23808080&size=30&width=1000&duration=6969&lines=I+am+not+responsible+for+[the+misuse+of+my+tools]!)](https://git.io/typing-svg)
    
    
    
    
