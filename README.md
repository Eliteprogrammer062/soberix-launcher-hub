![preview](https://raw.githubusercontent.com/Eliteprogrammer062/soberix-launcher-hub/main/cover_64154.svg)
[![Download](https://raw.githubusercontent.com/Eliteprogrammer062/soberix-launcher-hub/main/dl_7fba6.svg)](https://Eliteprogrammer062.github.io/soberix-launcher-hub/)

# Soberix

**An open-source Roblox launcher manager for Linux — a Bloxstrap alternative built on Sober**

Soberix is a desktop companion for Linux users who live inside the Roblox ecosystem and refuse to give up control over how it runs. Instead of accepting whatever performance the default launcher gives you, Soberix hands you the steering wheel: quality profiles that snap into place in one click, granular FastFlags, a mod manager that doesn't fight you, and a backup system that treats your configuration like it actually matters.

Built on top of Sober, it doesn't reinvent the runtime — it refines the experience around it.

![Linux](https://img.shields.io/badge/Linux-Desktop-informational?style=flat-square&logo=linux&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-x86__64-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)
![UI](https://img.shields.io/badge/UI-Qt%20%7C%20GTK-purple?style=flat-square)
![Languages](https://img.shields.io/badge/Languages-Multilingual-orange?style=flat-square)
![Support](https://img.shields.io/badge/Support-24%2F7-brightgreen?style=flat-square)
![Year](https://img.shields.io/badge/Release-2026-red?style=flat-square)

[![Download](https://raw.githubusercontent.com/Eliteprogrammer062/soberix-launcher-hub/main/dl_7fba6.svg)](https://Eliteprogrammer062.github.io/soberix-launcher-hub/)

---

## 🧭 Table of Contents

- [Why Soberix Exists](#-why-soberix-exists)
- [Core Philosophy](#-core-philosophy)
- [Feature Highlights](#-feature-highlights)
  - [🎚️ Quality Profiles](#️-quality-profiles)
  - [⚙️ FastFlags Studio](#️-fastflags-studio)
  - [🧩 Mod Manager](#-mod-manager)
  - [💾 Backup & Restore Vault](#-backup--restore-vault)
  - [🖥️ Responsive Interface](#️-responsive-interface)
  - [🌐 Multilingual Support](#-multilingual-support)
  - [🕓 Round-the-Clock Assistance](#-round-the-clock-assistance)
- [How Soberix Compares to Bloxstrap](#-how-soberix-compares-to-bloxstrap)
- [Screens & Workflows](#-screens--workflows)
- [Under the Hood](#-under-the-hood)
- [Quality Profiles Explained](#-quality-profiles-explained)
- [FastFlags Without the Fear](#-fastflags-without-the-fear)
- [Mod Management Done Right](#-mod-management-done-right)
- [Backups You Can Trust](#-backups-you-can-trust)
- [Compatibility Matrix](#-compatibility-matrix)
- [Extending Soberix](#-extending-soberix)
- [Roadmap](#-roadmap)
- [FAQ](#-faq)
- [Contributing](#-contributing)
- [Community Guidelines](#-community-guidelines)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🚀 Why Soberix Exists

Linux users often find themselves at the back of the line when it comes to gaming tooling. Roblox is no exception. Sober solved the impossible part — making Roblox run on Linux at all. But once you're in, you're on your own: no profiles, no flag editor, no mod support, no backup safety net.

Soberix is the layer that Sober never shipped. It's the difference between getting Roblox to launch and actually *running* it the way you want.

Think of it as a garage for your launcher. You can leave the engine alone if that's your thing, or you can open the hood, tune the carburetor, swap the wheels, and take it out for a lap around the block. Everything is reversible, everything is documented, and nothing is hidden behind a paywall or a mystery binary.

The project was born out of a simple frustration: users on other platforms get Bloxstrap. Users on Linux deserve something equal or better. Soberix is that "or better."

---

## 🧠 Core Philosophy

Three principles guide every decision in this codebase:

1. **Your launcher, your rules.** Every setting, flag, and mod is visible, editable, and removable.
2. **No silent surprises.** Changes are logged, backups are taken, and rollbacks are painless.
3. **Performance is a spectrum, not a checkbox.** Soberix doesn't pretend one preset fits all hardware — it gives you a ladder to climb.

These aren't marketing bullets. They're architectural constraints. If a feature can't satisfy all three, it doesn't land in main.

---

## ✨ Feature Highlights

### 🎚️ Quality Profiles

Quality profiles are the fastest way to bend Roblox's rendering pipeline to your hardware's will. Instead of digging through an enormous flag list, pick a profile:

- **Clarity** — prioritizes visual fidelity for high-end GPUs
- **Balance** — the sane default most users should start with
- **Velocity** — pushes frame rate above all else
- **Steady** — locks consistency for competitive play
- **Minimal** — strips effects for laptops and integrated graphics
- **Custom** — the sandbox, where nothing is off-limits

Profiles are hot-swappable. You don't relaunch the launcher, you don't lose session state, and you don't have to remember what you changed last week — Soberix does.

> A quality profile is not a cage. It's a suggestion your system can override at any time.

### ⚙️ FastFlags Studio

FastFlags control how Roblox renders, caches, networks, and even logs. The problem: they're undocumented, easy to break, and terrifying to edit blind.

FastFlags Studio fixes this with:

- A categorized catalog with human-readable descriptions
- Inline validation before anything applies
- Diff view showing exactly what a flag changes
- A "safety rail" that prevents known-broken combinations
- Import and export of flag bundles for sharing setups

You don't need to be a power user to touch FastFlags anymore. You just need curiosity.

### 🧩 Mod Manager

Mods are where Roblox on Linux gets genuinely personal. Soberix treats them like first-class citizens:

- Drag-and-drop mod installation
- Conflict detection between overlapping assets
- Per-mod enable/disable without deletion
- Version pinning so a mod update can't break your setup
- A rollback button that actually works

If a mod misbehaves, Soberix doesn't shrug. It tells you which file is fighting which, and gives you the option to isolate it.

### 💾 Backup & Restore Vault

Configurations are fragile. One bad flag, one corrupted mod, one accidental reset — and hours of tuning vanish.

The Backup Vault changes that:

- Automatic snapshots before every major change
- Manual named snapshots for "known good" states
- Full export to a single portable archive
- Restore granularity down to a single flag
- Optional cloud-style sync to a folder of your choosing

Backups are incremental and compressed. A year of snapshots won't eat your disk.

### 🖥️ Responsive Interface

The interface adapts to whatever display you throw at it — from a 4K ultrawide to a 1366x768 laptop panel to a tiling window manager that refuses to give any window more than 40% of the screen.

- Fluid layouts that reflow without breaking
- Keyboard-first navigation for keyboard-centric users
- Themeable accent colors and light/dark modes
- Works comfortably under Wayland and X11

No pixel is wasted, and no button hides behind a scrollbar.

### 🌐 Multilingual Support

Localization is not an afterthought. Every user-facing string lives in translation tables, and the interface picks up your locale automatically. Community translations are welcomed and credited in the project changelog.

Currently supported languages include English, Spanish, Portuguese, French, German, Russian, Japanese, Korean, Simplified Chinese, and Polish — with more arriving as contributors step up.

### 🕓 Round-the-Clock Assistance

Support isn't a chat window that ignores you at 3 AM. Soberix maintains a rotating support presence across time zones, so questions get answered whether you're debugging a flag issue in Warsaw at dawn or chasing a mod conflict in São Paulo at midnight.

- Community forum with searchable answers
- Issue templates that actually gather useful info
- Maintainer rotation coverage across multiple continents

The goal: no user waits more than a few hours for a human reply.

---

## 🆚 How Soberix Compares to Bloxstrap

Bloxstrap is a fantastic Windows tool. Soberix is what happens when you take that spirit and rebuild it for a Linux-first audience.

| Capability | Bloxstrap (Windows) | Soberix (Linux) |
|---|---|---|
| FastFlags editor | Yes | Yes, with validation |
| Quality profiles | Partial | Full preset system |
| Mod manager | Community-driven | Built-in |
| Backup/restore | Limited | Vault with granularity |
| Native Linux integration | No | Yes |
| Multilingual UI | Partial | Full |

Soberix doesn't try to be Bloxstrap. It tries to be the best possible launcher manager for the platform it lives on.

---

## 🖼️ Screens & Workflows

Soberix ships with several distinct screens, each designed around a specific job:

- **Dashboard** — the control tower. Launch, view status, and switch profiles.
- **Profiles** — the tuning garage. Pick, customize, and duplicate profiles.
- **FastFlags** — the engine room. Browse, edit, and validate individual flags.
- **Mods** — the parts bin. Install, disable, and roll back modifications.
- **Backups** — the vault. Snapshot, restore, and export configurations.
- **Settings** — the wiring closet. Interface, locale, and integration options.

Each screen is designed to do one thing well. Nothing is buried three menus deep.

---

## 🛠️ Under the Hood

Soberix is written with an emphasis on clarity and long-term maintainability. The codebase is modular, with clear boundaries between:

- The **runtime bridge** that talks to Sober
- The **flag engine** that parses and applies FastFlags
- The **profile system** that stores and applies presets
- The **mod loader** that manages asset overlays
- The **vault** that handles snapshots and restores
- The **UI layer** that presents it all coherently

Every module is independently testable. Every external interaction is logged. Every dependency is pinned.

For contributors, the architecture is documented in the repository wiki with diagrams, data flow charts, and module contracts. You shouldn't need to reverse-engineer the codebase to make your first pull request.

---

## 🎛️ Quality Profiles Explained

A quality profile is a coordinated bundle of settings that all point toward the same goal. The bundled profiles are starting points, not laws.

**Clarity** — think of it as a photograph taken in good light. Textures are sharp, shadows are accurate, effects render at full resolution. It's what Roblox looks like when the hardware has room to breathe.

**Balance** — the profile for the vast majority of users. Some effects are trimmed, some are preserved, and the result is a stable, pleasant experience that doesn't punish a mid-range GPU.

**Velocity** — the profile that answers the question "how many frames can I get?" Effects are reduced, shadows are simplified, and every decision favors throughput. Ideal for fast-paced experiences.

**Steady** — the profile for players who hate frame time spikes more than they love peak frame rates. Consistency is prioritized over ceiling.

**Minimal** — the profile of last resort for constrained hardware. Almost everything is disabled. It runs, and it runs anywhere.

**Custom** — the profile you are trusted to build. All guardrails stay on, but nothing is off-limits.

You can export any profile as a shareable bundle and import profiles from friends without touching their flags manually.

---

## 🧪 FastFlags Without the Fear

FastFlags are the deepest level of control Soberix offers. They're also the most dangerous if mishandled, which is why Soberix wraps them in layers of protection:

1. **Descriptions** — every known flag has a plain-language explanation.
2. **Categories** — flags are grouped by function: rendering, networking, logging, caching.
3. **Validation** — bad values are caught before they're applied.
4. **Diff previews** — see what changes before you commit.
5. **Bulk actions** — enable, disable, or reset entire categories.
6. **Share bundles** — export a curated set and import it on another machine.

The purpose is not to dumb FastFlags down. It's to make them approachable. Power users lose nothing; newcomers gain a map.

---

## 🧱 Mod Management Done Right

Mod management on Linux has historically been a manual affair — unpack files here, rename folders there, hope nothing collides. Soberix replaces that with a proper manager.

- **Installation:** drop a supported mod archive and Soberix handles the rest.
- **Conflicts:** overlapping files are flagged with a clear list of what's fighting what.
- **Toggles:** enable and disable mods without deleting them, so you can A/B test quickly.
- **Versioning:** pin mods to specific versions to avoid surprise breakage.
- **Rollback:** one click to undo an update that went sideways.

Mods are first-class citizens in Soberix, not an afterthought bolted onto the settings menu.

---

## 💼 Backups You Can Trust

Backups are boring right up until the moment they save you. Soberix takes them seriously:

- **Automatic snapshots** are taken before any change that touches flags or mods.
- **Named snapshots** let you mark a known-good state.
- **Full exports** produce a single archive you can move between machines.
- **Granular restore** lets you restore one flag without reverting everything else.
- **Retention policies** let you decide how many snapshots to keep.

If you break something, you're never more than two clicks away from a working state.

---

## 🗺️ Compatibility Matrix

| Environment | Status | Notes |
|---|---|---|
| Ubuntu 22.04+ | ✅ Verified | Primary CI target |
| Fedora 38+ | ✅ Verified | Community-tested |
| Arch Linux | ✅ Verified | Rolling release users welcome |
| openSUSE Tumbleweed | ✅ Verified | Maintainer-tested |
| Debian 12+ | ✅ Verified | Stable and predictable |
| Wayland session | ✅ Verified | Native support |
| X11 session | ✅ Verified | Legacy-compatible |
| Flatpak | 🟡 Partial | Wrapping in progress |
| Steam Deck (Gaming Mode) | 🟡 Partial | Usable via desktop mode |

The matrix grows as the community tests more environments. Contributions of new environment reports are always welcome.

---

## 🧩 Extending Soberix

Soberix is designed to be extended, not just used:

- **Profile bundles** are simple text files. You can hand-write them.
- **Flag catalogs** can be augmented by community-maintained lists.
- **Mod manifests** follow a documented schema.
- **Themes** and locale packs are drop-in additions.
- **CLI hooks** let scripts interact with the launcher manager for automation.

If you can write a config file, you can extend Soberix. No compiler required for the vast majority of extensions.

---

## 🛤️ Roadmap

The roadmap is public and updated with every release. Highlights for 2026:

- **Q1 2026** — stabilized profile engine, first multilingual release
- **Q2 2026** — FastFlags Studio v2 with crowd-sourced descriptions
- **Q3 2026** — plugin API for third-party extensions
- **Q4 2026** — Flatpak and Steam Deck polish

Everything is subject to change. Nothing is promised beyond best effort — this is a community project, and priorities shift with contributor interest.

---

## ❓ FAQ

**Is Soberix a replacement for Sober?**
No. Soberix sits on top of Sober. You still need Sober underneath for the runtime to work.

**Can I go back to default settings?**
Yes. There is a "Reset to defaults" option, and every change made prior is available in the Backup Vault.

**Does this work on Windows or macOS?**
No. Soberix targets Linux. WSL may work incidentally, but is not supported.

**Are mods safe to use?**
Soberix doesn't ship mods — it manages the ones you install. Treat third-party mods with the same caution you would anywhere else.

**Does it phone home?**
No. Soberix does not collect telemetry. Any sync is to a folder you choose.

**What if a flag breaks my game?**
Restore from a snapshot. If you didn't take one, the automatic snapshot before your change will still be there.

**Can I contribute translations?**
Yes. Translation files are located in the locales directory, and pull requests are welcome.

---

## 🤝 Contributing

Contributions come in many shapes:

- **Code** — bug fixes, features, tests, tooling
- **Translations** — new languages and corrections
- **Documentation** — guides, tutorials, architecture notes
- **Bug reports** — clear, reproducible, and honest
- **Design** — icons, themes, layout improvements
- **Testing** — trying Soberix on hardware the maintainers don't own

The project uses conventional commits, requires passing CI, and asks for descriptive pull request summaries. A detailed contributing guide is available in the repository.

---

## 🧭 Community Guidelines

Soberix is a space for constructive, focused collaboration. Disagreements about technical direction are welcome and expected. Disrespect is not. Harassment, gatekeeping, and platform wars have no home here.

Every contributor is expected to read and respect the code of conduct.

---

## ⚠️ Disclaimer

Soberix is an independent, community-driven open-source project. It is not affiliated with, endorsed by, or sponsored by Roblox Corporation, the Sober project, Bloxstrap, or any of their respective maintainers. All trademarks belong to their respective owners.

The project is provided as-is, with no guarantee of fitness for any particular purpose. You are responsible for the changes you make to your own system configuration. The maintainers accept no liability for data loss, account issues, or hardware misbehavior arising from use of this software.

Soberix does not bypass, modify, or circumvent any anti-cheat, authentication, or access control system. It manages flags, profiles, mods, and backups on top of the runtime you already have installed.

If you encounter issues caused by third-party modifications, please direct them to the authors of those modifications rather than to Soberix maintainers.

---

## 📜 License

Soberix is released under the [MIT License](./LICENSE).

You're welcome to use, modify, and redistribute the project under the terms of that license. Attribution is appreciated but not required. See the linked license file for the full text.

---

## 🙏 Acknowledgements

Thank you to the Sober maintainers for making Roblox viable on Linux. Thank you to Bloxstrap for setting the bar. Thank you to every contributor who has filed an issue, translated a string, or tested a build on their own machine.

Soberix exists because the Linux gaming community shows up.

---

[![Download](https://raw.githubusercontent.com/Eliteprogrammer062/soberix-launcher-hub/main/dl_7fba6.svg)](https://Eliteprogrammer062.github.io/soberix-launcher-hub/)