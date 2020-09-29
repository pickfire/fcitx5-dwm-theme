# dwm fcitx5 theme

![screenshot](./screenshot.png)

## Install

```
git clone https://github.com/pickfire/fcitx5-dwm-theme ~/.local/share/fcitx5/themes/dwm
```

Add the following to your `~/.config/fcitx5/conf/classicui.conf`.

```ini
# True, if you want a vertical candidate list
Vertical Candidate List=False
Theme=dwm
```

Optionally move pinyin preedit display to applications supporting it, modify
`~/.config/fcitx5/conf/pinyin.conf`.

```ini
# Show preedit within application
PreeditInApplication=True
```

Based on <https://github.com/iovxw/fcitx5-simple-theme>.

## License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or distribute this software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.
