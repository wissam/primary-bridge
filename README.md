# primary-bridge

Wayland ↔ X11 **PRIMARY selection** sync for wlroots/Hyprland. Text-only, tiny, deduped.

## Why
Hyprland doesn’t bridge PRIMARY across XWayland; this fills the gap.

## Install
- Arch: `sudo pacman -S wl-clipboard xclip`
- Build: `go build -o primary-bridge ./cmd/primary-bridge`

## Run (systemd user)
See `packaging/primary-bridge.service`.
