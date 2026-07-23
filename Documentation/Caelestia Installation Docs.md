# Caelestia Installation Guide :-

## Check network connectivity and update packages

```shell
ping archlinux.org
sudo pacman -Syu
```

## Install all the dependencies

```shell
sudo pacman -S git curl wget perl xdg-utils make cmake gcc base-devel linux-headers fastfetch htop duf firefox spectacle ttf-jetbrains-mono-nerd
```

## Install paru as AUR Helper

```shell
sudo pacman -S --needed base-devel
git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si
paru --version
cd ..
rm -rf paru/
```

## Install caelestia

```shell
paru -S caelestia-cli
caelestia --version
caelestia install
caelestia --version
```

## Install Desktop Manager for login screen

```shell
sudo pacman -S sddm
sudo systemctl enable sddm
```

## Update packages once you are logged in.

```shell
sudo pacman -Syu
```

# Install a SDDM Login Screen theming :-

## Clone the repository and run its setup :-

```shell
bash -c "$(curl -fsSL https://raw.githubusercontent.com/keyitdev/sddm-astronaut-theme/master/setup.sh)"
```

## Copy other importants files :-

- Copy the wallpapers from `../Assets/Wallpapers` into `Pictures/Wallpapers`.
- Update the wallpaper accordingly.

