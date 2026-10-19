# Built-in features for memory-cabinet-os

Purpose: digital archiving

1. **organize a personal routine** — run memory-cabinet-os-workspace. It creates ~/Documents/memory-cabinet-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run memory-cabinet-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/memory-cabinet-os-session-plans/.
3. **check routine readiness** — run memory-cabinet-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/memory-cabinet-os-workspace features/memory-cabinet-os-plan features/memory-cabinet-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for digital archiving:

1. **GNOME Calendar** — org.gnome.Calendar
2. **Audacity** — org.audacityteam.Audacity
3. **Foliate** — com.github.johnfactotum.Foliate

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
