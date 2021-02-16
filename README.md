# Flatpak for Citra  Emulator

## Installation

This Flatpak is available on
[Flathub](https://flathub.org/apps/details/org.citra_emu.citra).

If you have previously installed the old Flatpak version from us, you need to first remove it using:

```bash
flatpak uninstall --user org.citra.citra-nightly
flatpak uninstall --user org.citra.citra-canary
```

After following the [Flatpak setup guide](https://flatpak.org/setup/),
you can install it by entering the following command in a terminal:

```bash
flatpak install --user flathub org.citra_emu.citra -y
```

Once the Flatpak is installed, you can run Citra using your desktop environment's
application launcher or by entering:

```bash
flatpak run --user org.citra_emu.citra
```

## Updating

This Flatpak follows the latest Citra version.
To update it, run the following command in a terminal:

```bash
flatpak update
```
