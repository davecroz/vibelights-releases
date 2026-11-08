# Changelog

What changed in each release of Vibelights, newest first.

## 0.2.0 (2026-11-08)

- Patch has a DMX Universe view: all 512 channels at a glance, showing which fixture uses each channel, what it does, and the value being sent. Drag a fixture (or several) to give it a new DMX Address, or double-click a free channel to add fixtures there
- The generic RGBW Par has a 5-channel mode (dimmer, red, green, blue, white), now the default for new Shows and when adding one. Shows saved before this gain the mode too, so their Pars can be switched to it

## 0.1.0 (2026-11-06)

- First release: Looks that stack, fade and Release, Pages of Look buttons, the Master and a live Stage Plan, driving DMX fixtures through an ENTTEC DMX USB Pro
- Program Mode: patch fixtures from the bundled Open Fixture Library or the profile builder, place them on the Stage Plan, and build Looks from Groups, Palettes and Direct Overrides, with Undo and Snapshots
- Effects: pulse, chase and colour drift with Spread, and strobe, all limited to 3 flashes a second unless raised in Settings
- Triggers: MIDI notes (from ProPresenter Macros, for example) recall or Release Looks or set the Master, learned with one press
- Show Export and Import, warning before an import would lose changes
- An iPad page for Run Mode and Look editing, paired by approving a code on the main Mac
- The app installs the Lighting Engine as a background service and keeps it up to date, and Check for Updates… installs new releases
