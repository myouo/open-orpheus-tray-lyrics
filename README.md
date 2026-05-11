# Open Orpheus Tray Lyrics

GNOME Shell extension for showing [Open Orpheus](https://github.com/YUCLing/open-orpheus) lyrics in the GNOME top panel.

This extension is an Open Orpheus companion plugin. It reads the current lyrics state written by Open Orpheus and renders the text directly in the GNOME top panel.

## Install Locally

```bash
gnome-extensions pack -f .
gnome-extensions install --force open-orpheus-tray-lyrics@myouo.shell-extension.zip
gnome-extensions enable open-orpheus-tray-lyrics@myouo
```

Open Orpheus writes the current tray lyrics state to:

```text
$XDG_RUNTIME_DIR/open-orpheus/tray-lyrics.json
```

For the Flatpak build, the extension also checks:

```text
$XDG_RUNTIME_DIR/app/io.github.yucling.open-orpheus/open-orpheus/tray-lyrics.json
```

The extension itself does not install or enable Open Orpheus. Install Open Orpheus separately from its own release channel.
