# Changelog

All notable changes to Lafee ElvUI Chat Frame are documented in this file.

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
