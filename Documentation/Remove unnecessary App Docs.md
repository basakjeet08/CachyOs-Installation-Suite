# Remove unnecessary apps which won't be used by are installed by default :-

## Before uninstalling anything check their names and dependencies :-

```shell
pacman -Q | grep -i <application_name>
pactree -r <application_name>
```

## Remove Code Oss and install VS Code instead :-

```shell
sudo pacman -Rns code
paru -S visual-studio-code-bin
which code
ls /usr/share/applications | grep code
```

## Remove Alacritty :-

```shell
sudo pacman -Rns alacritty
```

## Remove App Image Launcher :-

```shell
sudo pacman -Rns todoist-appimage appimagelauncher
```

## Remove Btop :-

```shell
sudo pacman -Rns btop
```

## Remove Zed :-

```shell
sudo pacman -Rns zed
rm -rf ~/.config/zed
rm -rf ~/.local/share/zed
rm -rf ~/.cache/zed
```

## Remove CachyOs Hello :-

```shell
sudo pacman -Rns cachyos-hello
```

## Remove Firefox and its required firefox theme :-

```shell
sudo pacman -Rns firefox
sudo pacman -Rns caelestia-firefox-theme
```

## Remove Meld :-

```shell
sudo pacman -Rns meld
```

## Remove Shelly :-

```shell
sudo pacman -Rns shelly
```

## Remove Vim :-

```shell
sudo pacman -Rns cachyos-zsh-config
sudo pacman -Rns vim
```

## Remove VSCodium :-

```shell
sudo pacman -Rns vscodium-bin vscodium-bin-marketplace
rm -rf ~/.config/VSCodium
rm -rf ~/.cache/VSCodium
rm -rf ~/.vscode-oss
```
