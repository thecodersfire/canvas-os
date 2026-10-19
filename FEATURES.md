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

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
2. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
3. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
4. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
5. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
6. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
7. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
8. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
9. **Hydrogen** (org.hydrogenmusic.Hydrogen) — program drum patterns and percussion tracks.
10. **Guitarix** (org.guitarix.Guitarix) — shape guitar tone with amp and effects processing.
11. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
12. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
13. **GNOME Sound Recorder** (org.gnome.SoundRecorder) — capture voice and field notes.
14. **Flatseal** (com.github.tchx84.Flatseal) — review Flatpak app permissions.
15. **GNOME Calendar** (org.gnome.Calendar) — schedule sessions, deadlines, and events.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
