# Changelog

All notable changes to Lafee ElvUI Chat Frame are documented in this file.

## 1.2.0 - 2026-08-09

- Changed mover dimensions to represent the complete ElvUI chat panel, including the tab/title area.
- Added ElvUI-compatible inner margins so attached chat windows no longer overflow the right or bottom edges.
- Suppressed the attached undocked window background to avoid stacking it over the mover backdrop, and restore it when detached.
- Added persistent anchoring to the screen or any loaded ElvUI mover with configurable frame point, target point, and offsets.
- Preserved the current screen position when changing anchor targets or points and rejected circular anchors.

## 1.1.0 - 2026-08-09

- Added an individually configurable ElvUI background to every chat mover.
- Enabled backgrounds by default for both new and existing profiles.
- Synchronized background color with the current ElvUI Chat panel color and refreshed it after profile or theme changes.

## 1.0.2 - 2026-08-09

- Deferred plugin initialization until ElvUI has completed `E:Initialize`.
- Fixed a startup error caused by accessing `E.data` before ElvUI created its profile database.
- Added support for late addon loading when ElvUI is already initialized.

## 1.0.1 - 2026-08-09

- Stopped forcing the load-on-demand `ElvUI_Options` addon during startup.
- Added defensive plugin-option registration when another addon has loaded ElvUI options unusually early.
- Prevented a missing `E.Options.args.plugins` group from blocking this plugin's configuration panel.

## 1.0.0 - 2026-08-09

- Added one to four profile-aware ElvUI chat movers.
- Added persistent Blizzard ChatFrame assignment by window ID.
- Added safe handling for docking, closing, renaming, creation, reloads, profile changes, and combat deferral.
- Added ElvUI configuration, mover mode integration, reset confirmations, slash commands, and optional debug output.
- Added English, French, German, European and Latin American Spanish, Italian, Brazilian Portuguese, Russian, Korean, Simplified Chinese, and Traditional Chinese localizations.
- Added installation, architecture, compatibility, limitation, and in-game test documentation.
