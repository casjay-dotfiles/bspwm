## bspwm  
  
A tiling window manager based on binary space partitioning  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/bspwm/raw/master/install.sh)"
```
Manual install:
requires:    
```
apt install bspwm libnotify-bin catfish slimlock acpi-support wireless-tools gtk2-engine-murrine xfce4-terminal firefox xfce4-power-manager volumeicon-alsa xscreensaver policykit-1-gnome gnome-settings-daemon network-manager-gnome conky polybar xbindkeys tint2 
```  
```
yum install xfce4-power-manager gtk2-murrine-engine acpid wireless-tools xfce4-terminalfirefox  volumeicon xscreensaver policykit-1-gnome gnome-settings-daemon network-manager-gnome polybar xbindkeys tint2 
```  
```
pacman -S bspwm gtk-engine-murrine xfce4-power-manager acpi wireless-tools xfce4-terminal firefox volumeicon xscreensaver polkit-gnome gnome-settings-daemon network-manager-applet conky tint2 xbindkeys polybar 
```  
```
mv -fv "$HOME/.config/bspwm" "$HOME/.config/bspwm.bak"
git clone https://github.com/dfmgr/bspwm "$HOME/.config/bspwm"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/bspwm" target="_blank">bspwm wiki</a>  |  
  <a href="https://github.com/baskerville/bspwm" target="_blank">bspwm site</a>
</p>  
