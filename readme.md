IMPORTANT NOTE ON MONITOR CONTROL:
<br>
<br>
Monitor control is only hard-coded in .config/polybar/docky/config.ini. The rest is automated for a laptop (eDP\*) and HDMI monitor (HDMI\*).
<br>
<br>
The hard-coded part is the "monitor= _____" part of [bar/laptopbar] and [bar/monitorbar] in .config/polybar/docky/config.ini.
<br>
<br>
Note that .config/polybar/launch.sh looks to see if there is a monitor connected. If so, it uses [bar/laptopbar] and [bar/monitorbar]. Otherwise it uses [bar/main]. All three types are defined in .config/polybar/docky/config.ini.
