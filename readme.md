<img src="screen.png" alt="Preview">

<h2>IMPORTANT: Note on Monitor Control</h2>
<br>
Monitor control is only hard-coded in .config/polybar/docky/config.ini. The rest is automated for a laptop (eDP*) and HDMI monitor (HDMI*).
<br>
<br>
The hard-coded part is the "monitor= _____" part of [bar/laptopbar] and [bar/monitorbar] in .config/polybar/docky/config.ini.
<br>
<br>
Note that .config/polybar/launch.sh looks to see if there is a monitor connected. If so, it uses [bar/laptopbar] and [bar/monitorbar]. Otherwise it uses [bar/main]. All three types are defined in .config/polybar/docky/config.ini.
<br>
<br>
<h2>Dependencies:</h2>
bspwm/sxhkd<br>
polybar<br>
compton<br>
rofi<br>
polybar-themes<br>
i3lock<br>
imagemagick<br>
scrot<br>
wmctrl<br>
xprop<br>
slop
<br>
<br>
<h2>Other:</h2>
Theme: Graphite https://github.com/vinceliuice/Graphite-gtk-theme<br>
Icons: Tela-grey-dark<br>
Font: Iosevka<br>
File Browser: Thunar<br>
Color Scheme: Chalky (part of Gogh)<br>


