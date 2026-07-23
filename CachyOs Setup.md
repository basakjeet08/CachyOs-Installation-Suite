# Change default applications :-

## Zen Browser :-

### Check if Zen is already the default browser :-

```shell
xdg-settings get default-web-browser
```

### Check Zen application name :-

```shell
ls usr/share/applications | grep -i zen
```

### Set Zen as default browser :-

```shell
xdg-settings set default-web-browser <application-name>
```

### Verify Change :-

```shell
xdg-settings get default-web-browser
```


# Change hyprland and Caelestia configs :-

## Check for hyprland managed vs Caelestia user configs :-

```shell
ls ~/.config/hypr
ls ~/.config/caelestia
```

## Compare the files side by side and update Caelestia user configs :-

- Change which `browser` the browser shortcut opens.
- Change `terminal` shortcut to `Win + Enter`.
- Change which `editor` the editor shortcut opens.
- Change file explorer into `Thunar`.

