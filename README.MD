# Hyprland setup

<https://wiki.hyprland.org/Getting-Started/Installation/>

If you start from Sway like me, simply install yay.

`pacman -S yay`

## Things to install

```bash
yay -S pkg-config hyprland-bin xdg-desktop-portal-hyprland-git nwg-look-bin ffmpeg wf-recorder kitty wlogout        \
waybar-hyprland swaylock-effects swaybg playerctl noise-suppression-for-voice       \
grimblast-git swaybg sddm neovim pavucontrol pamixer 
```

## SDDM Theme

https://github.com/Keyitdev/sddm-astronaut-theme

## Icon theme

<https://github.com/linuxdeepin/deepin-icon-theme>

`yay -S deepin-icon-theme`

Change it in nwg-look! (It will be the `Bloom` theme)

## Widgets theme

I simply use `Matcha-dark-azul` since it fit perfectly with the bloom icon theme

## Apply Themes

### Pcmanfm

Simply use `nwg-look` for icon and global theme

### Dolphin

P.S. Pcmanfm feel better and easier to setup and use

`yay -S qt5ct`
`yay -S dolphin`

- `qt5ct` to edit icons
- `Kvantum Manager` to change global theme
