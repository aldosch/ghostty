# 👻 ghostty

aldo's [ghostty](https://ghostty.org) terminal config.

![example screenshot](/screenshot.png)

## what's here

- `config` — the main config
- `themes/` — `aldo-dracula` (dark) and `aldo-dracula-light` (light)

## notable bits

- theme follows the macos appearance: `dark:aldo-dracula,light:aldo-dracula-light`
- geist mono at 20pt, generous window padding
- window buttons and titlebar proxy icon hidden, blank title for a clean look
- macos-style text editing keybinds mapped to the usual readline escapes:
  - `cmd+left`/`cmd+right` — start/end of line
  - `opt+backspace`/`cmd+backspace` — delete word/line back
  - `opt+delete`/`cmd+delete` — delete word/line forward

## install

clone into `~/.config/ghostty`:

```bash
git clone git@github.com:aldosch/ghostty.git ~/.config/ghostty
```

config options are documented at https://ghostty.org/docs/config.
</content>
