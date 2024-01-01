# 🪄 Sei

this is another dwm fork from another user because i dont undenstand c or how dwm patch works

changes:
- change all keys for my taste
- fix monocle (the original idk dosent work so i just copy the monocle func from [dwm-luke-fork](github.com/sarajevo1914/dwm-luke-fork), seem works so i leave that
-

## Installation

```bash
git clone https://github.com/Fuwn/seiwm.git
cd seiwm
sudo make install
```

Also available is a [`PKGBUILD`](https://wiki.archlinux.org/title/PKGBUILD),
usable on distributions with
[`pacman`](https://wiki.archlinux.org/title/Pacman). Executing
`makepkg -si` will install both Sei and all build dependencies.

### Build Dependencies

- [freetype2](https://freetype.org/)
- [libx11](https://x.org/releases/current/doc/libX11/libX11/libX11.html)
- [libxft](https://gitlab.freedesktop.org/xorg/lib/libxft)

## Patches

- [xresources](https://dwm.suckless.org/patches/xresources/): Applies colours
  and other variables (i.e. using [`pywal`](https://github.com/dylanaraps/pywal)
  , etc.)
- [scratchpad](https://dwm.suckless.org/patches/scratchpad/): Accessible using
  <kbd>mod+shift+enter</kbd>
- [fibonacci](https://dwm.suckless.org/patches/fibonacci/),
  [deck](https://dwm.suckless.org/patches/deck/),
  [centeredmaster](https://dwm.suckless.org/patches/centeredmaster/), and more:
  New layout options bound to keys
  - [actualfullscreen](https://dwm.suckless.org/patches/actualfullscreen/): Using
 - [sticky](https://dwm.suckless.org/patches/sticky/): Persist window across all
 - [statuscmd](https://dwm.suckless.org/patches/statuscmd/): A clickable status
  bar, applied if using Luke Smith's build of [dwmblocks](https://github.com/lukesmithxyz/dwmblocks)
- [hide vacant tags](https://dwm.suckless.org/patches/hide_vacant_tags/): Hides
  tags with no windows
- [stacker](https://dwm.suckless.org/patches/stacker/): Move windows up the
 - [shiftview](https://dwm.suckless.org/patches/nextprev/): Cycle through tags
 - [vanitygaps](https://dwm.suckless.org/patches/vanitygaps/): Gaps allowed
  across all layouts
- [swallow](https://dwm.suckless.org/patches/swallow/): Replaces terminal with
  program if spawned from terminal
- [systray](https://dwm.suckless.org/patches/systray/): Functional system tray
- [bidi](https://dwm.suckless.org/patches/bidi/): Bidirectional text support
- [barpadding](https://dwm.suckless.org/patches/barpadding/): Padding for status
  bar
- [winicon](https://dwm.suckless.org/patches/winicon/): Active window icon shown
  in status bar
