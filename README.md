# alacritty

Alacritty setup

Includes color-schemes that can be activated used this [script](https://github.com/abeldekat/scripts/blob/main/alacritty_menu_owns).

## Install

Clone the repo to `~/.config/alacritty`.

Modify alacritty.toml, replace `CHANGE` with your username:

```toml
import = ["/home/CHANGE/.config/alacritty/colors.toml", "/home/CHANGE/.config/alacritty/device.toml"]
```

`Alacritty.toml` imports `colors.toml` and `device.toml`.

Link either `pc.toml` or `laptop.toml` to `device.toml`:

```sh
ln -sf pc.toml device.toml
```

## Defaults

- Colors: `catppuccin-frappe`
- Font: `Jetbrains Mono Medium`
