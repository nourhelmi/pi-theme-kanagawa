# pi-theme-kanagawa

[Kanagawa](https://github.com/rebelot/kanagawa.nvim) for the [pi](https://github.com/earendil-works/pi) coding agent: ink-dark background (`#1F1F28`), fuji-white text, gold borders (`#C0A36E`), surimi-orange accents.

Pairs with herdr's built-in `kanagawa` theme for a matching multiplexer:

```toml
# ~/.config/herdr/config.toml
[theme]
name = "kanagawa"

[theme.custom]
accent = "#C0A36E"
```

## Install

```bash
pi install git:https://github.com/nourhelmi/pi-theme-kanagawa
```

Then set the theme in `~/.pi/agent/settings.json` (`"theme": "kanagawa"`) or via `/themes`.

## License

MIT
