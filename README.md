# Arquivos de configuração Sway

## Pacotes necessários
```BASH
sudo dnf in -y \
mesa-dri-drivers glx-utils plymouth-system-theme \
sway swayidle swaylock i3status \
@fonts mozilla-fira-sans-fonts fira-code-fonts fontawesome5-fonts-all \
alacritty \
xdg-utils xdg-desktop-portal-gtk xdg-desktop-portal-wlr \
dunst \
pipewire pipewire-pulseaudio pulseaudio-utils pavucontrol playerctl \
grim slurp wl-clipboard imv wlsunset zathura-pdf* \
qt5-qtwayland qt5ct kvantum \
arc-theme papirus-icon-theme breeze-cursor-theme xsettingsd \
flatpak \
polkit-gnome \
wofi \
NetworkManager-tui \
tlp \
java-latest-openjdk-devel \
micro \
bash-completion
```
## Flatpak
```BASH
(sudo) flatpak remote-add flathub https://flathub.org/repo/flathub.flatpakrepo

flatpak install org.mozilla.firefox io.mpv.Mpv org.freedesktop.Platform.ffmpeg-full
```

## Firefox (Aceleração por Hardware)
```
gfx.webrender.all
gfx.webrender.compositor.force-enabled
media.ffmpeg.vaapi.enabled
full-screen-api.ignore-widgets
```

## Print
![](https://raw.githubusercontent.com/pedroigorreis/sway/main/print.png)
