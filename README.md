## Requirements

- i3wm
- i3status
- alacritty
- xtrlock
- rofi
- brightnessctl
- dunst
- blueman
- scrot
- xautolock
- picom

## Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/i3wm-setup.git
```

2. Copy configuration files:

```bash
mkdir -p ~/.config/i3 ~/.config/i3status
cp -r i3wm-setup/i3/config ~/.config/i3/
cp -r i3wm-setup/i3status/config ~/.config/i3status/
```

3. Restart i3:

```bash
i3-msg restart
```

## Key Bindings

- `Alt+Enter`: Open terminal (Alacritty)
- `Alt+d`: Application launcher (Rofi)
- `Alt+hjkl`: Vim-style window navigation
- `Alt+Shift+hjkl`: Move windows (Vim-style)
- `Alt+Shift+x`: Lock screen
- `Alt+r`: Resize mode
- `Alt+-`: Scratchpad show
- `Alt+Shift+-`: Scratchpad hide
- `Print`: Fullscreen screenshot
- `Shift+Print`: Area screenshot
