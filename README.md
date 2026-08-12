# Base16 Fuzzel

This is meant to be used with [tinted-theming](https://github.com/tinted-theming/home).

## Usage

Include theme on your fuzzel config `~/.config/fuzzel/fuzzel.ini`

```ini
[main]
include = "~/.config/fuzzel/colors.ini"
```

Apply with [Tinty](https://github.com/tinted-theming/tinty) `~/.config/tinted-theming/tinty/config.toml`

```toml
[[items]]
name = "fuzzel"
path = "https://github.com/jaycem-dev/base16-fuzzel"
themes-dir = "themes"
hook = "cp -f %f ~/.config/fuzzel/colors.ini"
supported-systems = ["base16"]
```
