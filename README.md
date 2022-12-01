# Hostyn Theme

> A minimalist spotlight based rofi theme

![Hostyn Light](/screenshots/hostyn-light.jpg "Hostyn Light")

## Requisites

This theme uses [UbuntuMono Nerd Font](https://github.com/ryanoasis/nerd-fonts) to display the icons. If you use Arch you can install `nerd-fonts-ubuntu`([AUR](https://aur.archlinux.org/packages/nerd-fonts-ubuntu))

For the blur you will need to configure picom.

```js
// picom.conf
blur-strength = 5
blur-background = true
```

## Installing theme

1. Clone this repository.

```bash
git clone https://github.com/hostyn/rofi-hostyn-theme.git
cd rofi-hostyn-theme
```

2. Create the theme directory if you don't have it.

```bash
mkdir -p ~/.local/share/rofi/themes/
```

3. Copy the themes to `~/.local/share/rofi/themes/` folder.

```bash
cp themes/* ~/.local/share/rofi/themes/
```

4. Run `rofi-theme-selector`, select the theme you want with `Enter` and confirm with `Alt-a`.
