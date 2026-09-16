# pi-gruvbox

![Warning: Vibe Coded](https://img.shields.io/badge/%E2%9A%A0%EF%B8%8F_warning-vibe_coded-orange?style=flat)

[Gruvbox Dark](https://github.com/morhetz/gruvbox) theme for [pi](https://pi.dev), built on the
classic morhetz palette — the same one used by the `gruvbox-dark` bat theme and the gruvbox
Starship preset.

Bright variants for text and syntax, muted variants for chrome, authentic gruvbox backgrounds
(`#1d2021` / `#282828` / `#3c3836`).

## Install

```bash
pi install npm:pi-gruvbox        # from npm
# or
pi install git:github.com/astrojuanlu/pi-gruvbox   # from git
# or
pi install /path/to/pi-gruvbox   # local checkout
```

Then select **gruvbox-dark** in pi via `/settings`, or set it directly:

```json
{ "theme": "gruvbox-dark" }
```

> If you previously copied the theme file into `~/.pi/agent/themes/`, delete that copy — a
> package and a loose file defining the same theme name will shadow each other.

## Try without installing

```bash
pi --theme /path/to/pi-gruvbox/themes --use-theme gruvbox-dark
```

## Preview

| Token | Color |
|-------|-------|
| accent / warning | `#fabd2f` gruvbox bright yellow |
| success / strings | `#b8bb26` bright green |
| error / keywords | `#fb4934` bright red |
| links / variables | `#83a598` bright blue |
| numbers | `#d3869b` bright purple |
| operators | `#8ec07c` bright aqua |
| comments / muted | `#928374` gray |
| text | `#ebdbb2` fg1 |
