## Install

As root;
```
# curl -LO https://raw.githubusercontent.com/pm-lack/pm-larbs/refs/heads/main/pm-larbs.sh
# sh pm-larbs.sh
```

## Keybinds

Common
- Mod+Enter,            Spawn terminal (the default terminal is st)
- Mod+q,                Close window
- ModShift+q,           Close window
- Mod+d,                dmenu
- ModShift+d,           dmenu
- Mod+j,                Cycle thru windows by stack order
- Mod+k,                Cycle thru windows by reverse stack order
- Mod+space,            Make selected window the master
- Mod+h,                Decrease width of master window
- Mod+l,                Increase width of master window
- Mod+z,                Increase gaps (may also hold Mod and scroll mouse)
- Mod+x,                Decrease gaps (may also hold Mod and scroll mouse)
- Mod+a,                Toggle gaps
- ModShift+a,           Default gaps
- ModShift+space,       Make focused window float
- Mod+s,                Toggle “sticky” window (follows you from tag to tag)
- Mod+b,                Toggle statusbar (may also middle click on desktop)

Layout & Navigation
- Mod+y,                Fibonacci spiral mode
- ModShift+y,           Tiling mode
- Mod+u,                Dwindle mode
- ModShift+u,           Centeredmaster mode
- Mod+f,                Toggle fullscreen
- Mod+o,                Increase the number of master windows
- ModShift+o,           Decrease the number of master windows
- Mod+tab,              Go to previous tag
- Mod+backslash,        Go to previous tag
- Mod+g,                Go to left tag
- Mod+page_up,          Go to left tag
- ModShift+g,           Send focused window to left tag
- ModShift+page_up,     Send focused window to left tag
- Mod+semicolon,        Go to right tag
- Mod+page_down,        Go to right tag
- ModShift+semicolon,   Send focused window to right tag
- ModShift+page_down,   Send focused window to right tag
- Mod+left,             Go to left display
- Mod+right,            Go to right display
- ModShift+left,        Move window to left display
- ModShift+right,       Move window to right display

Basic Programs
- Mod+r,                lf (terminal-based file browser/manager)
- ModShift+b,           Web browser (Zen by default)
- ModShift+v,           Vesktop (better discord client)
- Mod+t,                Thunar (gui file explorer)
- ModShift+w,           nmtui (for connecting to wireless internet)
- ModShift+Enter,       Toggle dropdown terminal
- Mod+m,                Spawn ncspot (terminal-based spotify client)

System
- Mod+backspace,        Choose to lock screen, logout, shutdown, reboot, etc.
- Mod+F3,               Select screen/display to use
- Mod+F4,               pulsemixer (audio control)
- Mod+F5,               Reload xresources
- Mod+F9,               Mount a USB drive/hard drive or Android
- Mod+F10,              Unmount a non-essential drive or Android
- Mod+F11,              View webcam
- Mod+F12,              Rerun keyboard mapping scripts if new keyboard is attached
- Mod+insert,           Show contents of clipboard/primary selection
- Mod+print,            Take a screenshot
- ModShift+print,       Select area to screenshot

Audio
- Mod+minus,            Decrease volume 5%
- ModShift+minus,       Decrease volume 15%
- Mod+equal,            Increase volume 5%
- ModShift+equal,       Increase volume 15%
- ModShift+m,           Mute all audio
