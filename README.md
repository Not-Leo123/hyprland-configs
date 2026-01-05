# hyprland-configs
my hyprland config


do:  sudo pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si

then : yay -S kitty hyprland waybar rofi swaylock waybar

after do: hyprctl reload
