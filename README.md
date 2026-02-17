# Dogi for Ghostty

Ghostty port of the Dogi Zed theme.

## Included Themes

- `themes/dogi-dark`
- `themes/dogi-light`

## Install

1. Create Ghostty's custom themes directory:
   `mkdir -p ~/.config/ghostty/themes`
2. Copy the files from this repository's `themes/` directory into `~/.config/ghostty/themes`
3. In `~/.config/ghostty/config`, set automatic dark/light switching:

```conf
theme = light:dogi-light,dark:dogi-dark
```

Or use a single theme:

```conf
theme = dogi-dark
```

## Source Theme

Original Zed theme: https://github.com/DogukanUrker/DogiZed
