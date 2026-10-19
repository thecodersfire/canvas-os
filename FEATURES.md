# Built-in features for Canvas-OS

Purpose: digital art, video editing, 3D work, and recording

1. **prepare a creative project** — run canvas-os-workspace. It creates ~/Documents/canvas-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run canvas-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/canvas-os-session-plans/.
3. **check project and export readiness** — run canvas-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/canvas-os-workspace features/canvas-os-plan features/canvas-os-check "$HOME/.local/bin/"
