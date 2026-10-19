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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for digital archiving:

1. **Zotero** — manage research sources and citations (org.zotero.Zotero)
2. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)
3. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
4. **Thonny** — write and debug Python code (org.thonny.Thonny)
5. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
6. **QGIS** — analyze geographic data and make maps (org.qgis.qgis)
7. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
8. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
9. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
10. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
