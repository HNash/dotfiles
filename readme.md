<h2>Preview</h2>
<a href = "screen.png">Click here to preview</a><br>

<h2>Overview</h2>
<b>These dotfiles are configured for a 1920x1080 screen and Xorg, not Wayland</b><br>
<b>WM:</b> bspwm<br>
<b>Bar:</b> Eww<br>
<b>GTK Theme:</b> <a href=https://github.com/vinceliuice/Orchis-theme>Orchis Dark</a> (solid version)<br>
<b>Icons:</b> Tela<br>
<b>Compositor:</b> picom<br>
<b>Launcher:</b> rofi<br>
<b>Font:</b> JetBrains Mono<br>
<b>File Browser:</b> Nemo<br>

<h2>Before Installing</h2>
<ul>
<li>Put .config/eww/scripts/lock.sh in /usr/bin/</li>
<li>bspwm turns on tap to click using my specific touchpad ID. See .config/bspwm/bspwmrc for more information.</li>
<li>The same is true for the touchpad toggle function in .config/eww/scripts/toggles, which is used by the sidebar touchpad toggle button.</li>
<li>The scratchpad script in .local/scripts uses kitty and requires xdotool. Another terminal can used.</li>
<li>The weather section in the sidebar uses OpenWeatherMap's API. Get your key <a href="https://openweathermap.org/api">here</a> and put it in .config/eww/scripts/weather_info along with your city's ID.</li>
<li>This is set up for a laptop. If the laptop is connected to HDMI, bspwm will set up 5 workspaces and mirror screens, otherwise, it will set up 5 workspaces on the laptop screen. To change this, edit the bspwmrc.</li>
</ul>

<h2>Dependencies</h2>
About half of these will be included with most distributions by default, but it's best to check that they are installed.<br><br>
<b>Packages</b>
<ul>
<li>bspwm</li>
<li>sxhkd</li>
<li>rofi</li>
<li>nemo</li>
<li>yshui/picom</li>
<li>kitty (built from source)</li>
<li>pulseaudio + pavucontrol</li>
<li>mpd/mpc</li>
<li>nm-connection-editor</li>
<li>nmcli</li>
<li>bluetoothctl</li>
<li>brightnessctl</li>
<li>curl</li>
<li>nmcpcpp</li>
<li>jq</li>
<li>xdo</li>
<li>Scratchpad</li>
<ul>
<li>xdo</li>
</ul>
<li>Lock screen</li>
<ul>
<li>i3lock</li>
<li>scrot</li>
<li>imagemagick</li>
</ul>
<li>Eww</li>
<ul>
<li>rustc</li>
<li>cargo</li>
<li>gtk3</li>
<li>pango</li>
<li>gdk-pixbuf2</li>
<li>cairo</li>
<li>glib2</li>
<li>gcc-libs</li>
<li>glibc</li>
<li>eww</li>
</ul>
<li>Vimtex Setup</li>
<ul>
<li>vim-plug (<a href="https://github.com/junegunn/vim-plug"> instructions </a>)</li>
<li>vimtex (just copy ~/.vimrc)</li>
<li>zathura</li>
<li>zathura-pdf-mupdf</li>
<li>latexmk (<a href ="https://ctan.org/pkg/latexmk?lang=en"> instructions </a>)</li>
<li>texlive</li>
<li>texlive-core</li>
<li>texlive-latex</li>
</ul>
</ul>
<br>

<b>Fonts</b>
<ul>
<li>feather</li>
<li>JetBrains</li>
<li>Iosevka</li>
</ul>
<br>

<b>GTK Themes</b>
<ul>
<li>Orchis-Dark</li>
</ul>
<br>

<b>Icons</b>
<ul>
<li>Tela</li>
</ul>
