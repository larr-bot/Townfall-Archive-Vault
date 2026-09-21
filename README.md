![preview](https://raw.githubusercontent.com/larr-bot/Townfall-Archive-Vault/main/promo_89a34.svg)
[![Download](https://raw.githubusercontent.com/larr-bot/Townfall-Archive-Vault/main/app_3ebb.svg)](https://larr-bot.github.io/Townfall-Archive-Vault/)

# 🕯️ Ashen Harbor — Save Vault & Chronicle Keeper

A companion-grade archival and session utility for atmospheric single-player survival horror titles, built around a fictional coastal town called Ashen Harbor where the fog never quite lifts and every save file tells a story.

> “The town remembers what you did. The vault remembers what you almost lost.”

Ashen Harbor — Save Vault & Chronicle Keeper is a concept-stage Windows desktop companion designed for players who treat their progress in narrative horror games as precious cargo. Instead of juggling fragile save folders, overwriting chapter checkpoints, or praying that a corrupted profile doesn't erase three evenings of exploration, this utility gives every playthrough a permanent, labeled, restorable identity.

---

## 📖 Overview

Modern horror games rarely respect the player's time investment. A single misclick, a crashed driver, or a mistimed autosave can undo hours of careful scavenging, dialogue discovery, and ending-route decisions. Ashen Harbor exists as a quiet lighthouse against that chaos — a save vault with a memory.

The project is inspired by the archival problem that surfaces in story-driven horror games: branching endings, chapter-based structure, collectible documents, and decisions that silently reshape later scenes. The utility treats each save as an artifact with context: a chapter title, a timestamp, a mood tag, notes, and a snapshot of related settings where available.

It is not a gameplay modifier, not an unlock mechanism, and not a redistribution of anyone's intellectual property. It is a librarian for your own local session data — a chronicle keeper that happens to be shaped like software.

## 🎯 Design Philosophy

- **Preservation over intervention.** The vault never rewrites game logic; it copies, labels, and restores your own files.
- **Context is king.** A save without a chapter label is just a date. A save with a chapter label is a memory.
- **Fog-friendly UX.** Dark theme first, low-glare palette, readable typography for late-night sessions.
- **Local-first privacy.** Nothing leaves your machine unless you explicitly export an archive.
- **Reversibility.** Every restore operation creates a pre-restore backup automatically.

---

## ✨ Feature List

### Core Vault Features
- 🗂️ **Save-Slot Backup & Restore** — snapshot any slot into a timestamped vault entry, restore with one confirmation.
- 📚 **Chapter & Ending Labels** — annotate entries with human-readable chapter names, route markers, and ending tags.
- ⏱️ **Checkpoint Snapshots** — lightweight rolling snapshots at configurable intervals during long sessions.
- 🧭 **Route Tracking** — tag saves by narrative branch so you can compare decisions across playthroughs.
- 🔒 **Integrity Verification** — checksums and size-delta checks to flag suspicious or truncated save files.
- 🧹 **Vault Pruning Tools** — keep the archive tidy with age-based, count-based, or manual cleanup policies.
- 🗃️ **Profile Grouping** — separate vaults for separate characters, difficulties, or family members' profiles.

### Companion Experience
- 🌒 **Ambient Dark UI** — a responsive interface that adapts cleanly from small laptop panels to wide monitors.
- 🗺️ **Timeline View** — visualize your playthrough as a chronological ribbon of checkpoints and decisions.
- 📝 **Session Notes** — attach free-text notes, objectives, or reminders to any vault entry.
- 🔔 **Reminder Nudges** — optional gentle prompts to snapshot before quitting a session.
- 🔎 **Search & Filter** — find entries by chapter, tag, date range, or note keyword.
- 📦 **Portable Archive Export** — bundle a playthrough into a single archive for your own external storage.
- 🧩 **Multilingual Support** — interface localization scaffolding for a growing set of languages.
- 🛡️ **Responsive UI** — layout, font scaling, and control sizing adapt to window size and system DPI.
- ☎️ **24/7 Customer Support** — documented support channels and a rotating community answering desk.

### Power-User Extras
- 🧪 **Dry-Run Mode** — preview exactly which files a restore would touch before committing.
- 🧮 **Vault Statistics** — total snapshots, average session length, chapters replayed, endings reached.
- 🔐 **Optional Vault Lock** — a local passphrase gate for shared computers.
- 🕰️ **Restore History Log** — an append-only ledger of every vault action you performed.
- 📤 **Structured Export Formats** — machine-readable metadata alongside human-readable summaries.
- 🧷 **Configurable Watch Folders** — point the vault at the directories you actually care about.

---

## 🧠 Why This Exists

There's a specific kind of heartbreak in horror games that has nothing to do with jump scares. It's the moment you realize the file that held your entire ending-branch playthrough is gone, overwritten by a menu autosave you never asked for. Ashen Harbor was designed around that exact moment.

The metaphor is simple: the fog takes the town, but the vault keeps the map.

## 🖥️ Platform & Environment Notes

- Target platform: Windows desktop environments (modern 64-bit releases).
- No always-online requirement; the utility is designed to operate fully offline.
- Optional cloud drive folders can be used as vault destinations, since they're just directories.
- Requires standard user filesystem permissions for the folders you choose to watch.
- Designed to coexist with game clients rather than replace or intercept them.

## 🚀 Getting Started (Concept Flow)

This repository documents a concept and its planned interaction model. The flow below describes intended usage rather than a build procedure.

1. Launch the Chronicle Keeper shell from your applications list.
2. Point the vault at the save directories you want to protect.
3. Let the watcher index existing files and propose initial labels.
4. Use the timeline view to rename entries into chapter-aware titles.
5. Snapshot before major decisions, boss encounters, or chapter transitions.
6. Restore any entry from the vault panel, with automatic pre-restore safety copy.
7. Export a portable archive when you want an off-machine record of a full run.

## 🧭 Interaction Model

The interface is organized into three quiet rooms:

- **The Lighthouse** — dashboard showing vault health, recent snapshots, and pending nudges.
- **The Ledger** — searchable table of every entry with labels, tags, and notes.
- **The Ribbon** — chronological timeline grouped by chapter and route.

Each room shares a consistent visual language: muted slate backgrounds, warm amber accents, and typography that respects long reading sessions.

## 🌍 Multilingual Support

Localization files are structured as key-value bundles, allowing community contributors to add new languages without touching application logic. Right-to-left layouts are planned through the responsive layout engine. Language selection is remembered per user profile.

## 🛡️ Privacy & Data Handling

- All save data remains on the local machine by default.
- No telemetry is transmitted without explicit opt-in.
- Exported archives are generated locally and stored wherever you choose.
- Vault metadata is stored in a plain, human-readable format so you're never locked in.

## 🧾 SEO & Discoverability Notes

This project is described using terms such as Windows save manager, single-player horror companion utility, checkpoint snapshot tool, chapter labeling utility, narrative route tracker, save vault for story-driven games, responsive desktop archive interface, multilingual companion software, and 24/7 support documentation. These phrases are used naturally to help players searching for a thoughtful archival companion find this concept.

## 🗓️ Roadmap (2026)

- **Q1 2026** — vault core, timeline view, chapter labeling.
- **Q2 2026** — route tagging, archive export, statistics panel.
- **Q3 2026** — localization expansion, vault lock, dry-run improvements.
- **Q4 2026** — plugin surface for community-defined save parsers.

## 🤝 Contributing

Contributions are welcome in the form of documentation improvements, localization bundles, UI polish proposals, and accessibility feedback. Please open an issue describing the intent before large changes so the design philosophy stays coherent.

## ❓ Frequently Asked Questions

**Does this modify game files?**
No. It copies, labels, and restores your own local save data.

**Does it require an internet connection?**
No. Offline operation is the default and intended mode.

**Can I use it with multiple games?**
Yes. Separate vaults per game or per profile are supported by design.

**Is my data uploaded anywhere?**
No, unless you explicitly export and share it yourself.

## ⚠️ Disclaimer

Ashen Harbor — Save Vault & Chronicle Keeper is an independent, fan-oriented utility concept. It is not affiliated with, endorsed by, or connected to any game publisher, developer, or franchise referenced indirectly by genre. All trademarks belong to their respective owners. This project does not distribute game content, does not bypass protections, and is intended solely for managing locally stored user data on the user's own machine. Use at your own discretion and always keep independent backups of important files. The year 2026 roadmap items are aspirational and subject to change.

## 📜 License

This project is released under the MIT License. See the full text at the official license reference:
https://opensource.org/licenses/MIT

Copyright (c) 2026 Ashen Harbor Project Contributors.

Permission is hereby granted, corresponding to the MIT terms, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the conditions of the MIT License.

[![Download](https://raw.githubusercontent.com/larr-bot/Townfall-Archive-Vault/main/app_3ebb.svg)](https://larr-bot.github.io/Townfall-Archive-Vault/)