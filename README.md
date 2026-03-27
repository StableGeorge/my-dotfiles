Here are my dotfiles. To clone:
'''
git clone https://github.com/StableGeorge/my-dotfiles
'''

To copy:
'''
cd my-dotfiles
cp -r alacritty ~/.config/
cp -r rofi ~/.config/
cp -r qtile ~/.config/
cp Wallpaper.jpg ~/
'''

Dependencies for Basic Desktop Utilities on Arch Linux
'''
sudo pacman -S xserver-xorg lightdm lightdm-gtk-greeter alacritty qtile rofi feh picom xss-lock python-psutil
sudo systemctl enable lightdm.service
'''

Dependencies for Appearance:
'''
sudo pacman -S lxappearance materia-gtk-theme papirus-icon-theme ttf-font-awesome
'''

Installing Paru:
'''
sudo pacman -S --needed base-devel
git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si
'''

Installing AUR Tools:
'''
paru betterlockscreen
'''
