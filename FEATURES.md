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

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **Kamoso** (org.kde.kamoso) — capture webcam photos and short video clips.
2. **Kwave** (org.kde.kwave) — record and edit audio waveforms with basic filters and analysis.
3. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
4. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
5. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
6. **Gwenview** (org.kde.gwenview) — review image sets and make quick crop, resize, and annotation edits.
7. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
8. **Ark** (org.kde.ark) — open and create common project archive files.
9. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
10. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
11. **KolourPaint** (org.kde.kolourpaint) — make quick raster sketches, labels, and simple image edits.
12. **Elisa** (org.kde.elisa) — organize and play local music libraries.
13. **EasyEffects** (com.github.wwmm.easyeffects) — shape microphone and output audio with PipeWire effects.
14. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
15. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for digital art, video editing, 3D work, and recording. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **Shotcut** (org.shotcut.Shotcut) — Edit multitrack video with filters, transitions, and titles.
2. **HandBrake** (fr.handbrake.ghb) — Transcode video files to common formats and presets.
3. **OpenShot** (org.openshot.OpenShot) — Assemble video clips on a multitrack timeline.
4. **Glaxnimate** (org.kde.glaxnimate) — Create vector animations, motion graphics, and animated SVG assets.
5. **Subtitle Composer** (org.kde.subtitlecomposer) — Create and synchronize captions for video projects.
6. **KPhotoAlbum** (org.kde.kphotoalbum) — Tag and organize large photo collections.
7. **Kid3** (org.kde.kid3) — Edit audio tags and album metadata in batches.
8. **Loupe** (org.gnome.Loupe) — View images and make simple crop, rotate, or flip edits.
9. **Kasts** (org.kde.kasts) — Subscribe to podcasts and manage playback queues.
10. **Jellyfin Desktop** (org.jellyfin.JellyfinDesktop) — Browse and play personal media from a configured Jellyfin server.
11. **QGIS** (org.qgis.qgis) — Create and analyze geographic information system projects.
12. **GNOME Maps** (org.gnome.Maps) — Look up places and routes using online map data.
13. **Marble** (org.kde.marble) — Explore maps and a virtual globe for route and place context.
14. **KGeography** (org.kde.kgeography) — Practice place and map recognition.
15. **KGeoTag** (org.kde.kgeotag) — Review and edit photo location metadata.
