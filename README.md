☣️ **Spanner Machine** ☣️ 


# ⚒️ Hacking Environment Based on Openbox ⚒️

---

<p align="center">
<a href="https://github.com/tmcybers/a01-injection_exploit-owasp-top-10"><img src="https://img.shields.io/badge/python-3-yellowgreen">
<a href="https://github.com/tmcybers/a01-injection_exploit-owasp-top-10"><img src="https://img.shields.io/badge/downloads-34-green">
<a href="https://github.com/tmcybers/a01-injection_exploit-owasp-top-10"><img src="https://img.shields.io/badge/releases-1.0-red">
<a href="https://github.com/tmcybers/a01-injection_exploit-owasp-top-10"><img src="https://img.shields.io/badge/contributors-1-orange">
<a href="https://github.com/tmcybers/a01-injection_exploit-owasp-top-10"><img src="https://img.shields.io/badge/open%20issues-0-blue">
<a href="https://github.com/tmcybers/a01-injection_exploit-owasp-top-10"><img src="https://img.shields.io/badge/discussions-1-orange">
<a href="https://t.me/+l5WYQySOL-0yMDQ0"><img src="https://img.shields.io/badge/chat-online-brightgreen?style=plastic&logo=telegram">
<a href="https://twitter.com/tmcybers"><img src="https://img.shields.io/badge/folow-tmcyber-blue?style=plastic&logo=twitter">
<a href="https://ioc.exchange/@tmcyber"><img src="https://img.shields.io/badge/folow-tmcyber-blue?style=plastic&logo=mastodon">
<a href="https://tmcybers.github.io/blog"><img src="https://img.shields.io/badge/Write%20ups-Blog-red?style=plastic&logo=hackthebox">
  <a href="https://wakatime.com/@tmcyber"><img src="https://img.shields.io/badge/Developer-Blog-orange?style=plastic&logo=python">
<a href="https://tmcybers.github.io/Donate"><img src="https://img.shields.io/badge/support-tmcyber-blue?style=plastic&logo=donate">
<a href="https://ko-fi.com/tmcyber"><img src="https://img.shields.io/badge/Support%20me-Ko--Fi-brightgreen?style=plastic&logo=ko-fi">

</p>

* 🗿 My custom of what y use every day for 💉 hacking and threat hunting 🔫 is based on Debian/Parrot Os ↪️ Openbox tilling window*

↘️↘️↘️↘️↘️↘️↘️`Why openbox`↘️↘️↘️↘️↘️↘️↘️

### 🕶️ Openbox is the most lightweight tilling window [openbox offers you the freedom 🕶️ to work with shortcuts or mouse, your choice is your choice 🏆

  
              ☢️ `Never automate the installation of this type of customs can be broken depending on your system dependencies` ☢️
  
  
  
  ## Instalation proceed
```
sudo apt update
sudo parrot-upgrade
sudo apt install openbox
sudo apt install obconf lxinput
sudo apt install snapd
sudo snap install lsd
sudo apt install bat
sudo apt install kitty
sudo apt install rofi
sudo apt install mpd
sudo apt install flameshot
sudo apt install fonts-material-design-icons-iconfont

```

## Fonts [very important]
  
1.) Download some [Nerd Fonts](https://www.nerdfonts.com/)

2.) We need the fonts to be available system-wide, you'll need to copy them to `/usr/local/share/fonts` and reboot / or manually rebuild the font cache with `fc-cache -fv`

3.) Run the command `fc-cache -fv` to manually rebuild the font cache.

  
  
 ## Wallpaper manager
  
```
sudo apt install nitrogen
  
```
  
## Manger for Menu/Custom Themes and Icons
  
```
sudo apt install lxappearance lxappearance-obconf

```
  
## Wallpapers for Nitrogen

[positron-dream nord themes]( https://imgur.com/a/qrgtyDU)
  
  
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
### This is like mine is, it like an example, will add more later.
  
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
  

## Polybar Tun!!ing
  
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
  
 
## Kitty Tun!!!ng

[kitty-themes](https://github.com/dexpota/kitty-themes)
  
**in case that you don't have this archives simply create then***
  
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
   
  
* Im using DotGov as theme.  
  
  
## Picom transparency Tun!!!ng 

```
cd .config
mkdir picom
touch picom.conf
geany picom.conf
```
* Into picom.conf just paste my conf, and modelling to your liking.
  
* Sample here:
[picom sample](https://github.com/yshui/picom/blob/next/picom.sample.conf)
  
  
## Mosaic windows tilling [CTRL+1,2,3,4,45,5,6,7,8,9] 
 
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
  

  
## Custom Shortcuts
  
* rc.xml
  
* Example
  
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

 * Flameshot is the best tool for reports/write ups.  
    

    

    
    
 
  
  

  
