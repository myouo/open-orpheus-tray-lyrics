# Open Orpheus Tray Lyrics

GNOME Shell extension for showing Open Orpheus lyrics in the GNOME top panel.

## Install Locally

```bash
gnome-extensions pack -f .
gnome-extensions install --force open-orpheus-tray-lyrics@open-orpheus.shell-extension.zip
gnome-extensions enable open-orpheus-tray-lyrics@open-orpheus
```

Open Orpheus writes the current tray lyrics state to:

```text
$XDG_RUNTIME_DIR/open-orpheus/tray-lyrics.json
```

