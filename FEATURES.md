# Built-in features for Canvas-OS

Purpose: digital art, video editing, 3D work, and recording

1. **prepare a creative project** — run canvas-os-workspace. It creates ~/Documents/canvas-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run canvas-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/canvas-os-session-plans/.
3. **check project and export readiness** — run canvas-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/canvas-os-workspace features/canvas-os-plan features/canvas-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for digital art, video editing, 3D work, and recording:

1. **GIMP** — org.gimp.GIMP
2. **Inkscape** — org.inkscape.Inkscape
3. **Scribus** — org.scribus.Scribus

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for digital art, video editing, 3D work, and recording:

1. **Audacity** — edit audio recordings (org.audacityteam.Audacity)
2. **Ardour** — record and mix multitrack audio (org.ardour.Ardour)
3. **darktable** — develop RAW photos (org.darktable.Darktable)
4. **VLC** — review media files (org.videolan.VLC)
5. **Mixxx** — prepare and mix DJ sets (org.mixxx.Mixxx)
6. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
7. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
8. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
9. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
10. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
