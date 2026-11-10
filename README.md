# Roblox Controller v0.3

Window-aware battle macro with checkbox client selection, normal ball/healing controls and persistent diagnostics.

Start with `Start-Controller.cmd`. Follow [TESTING-v03.md](TESTING-v03.md): choose game windows, check layouts, then run one encounter first.

The installed layout check successfully read Magikarp and Yamper in two 800×599 client windows. This was a read-only check, not a verification of catching/healing menus or unattended automation.

Logs: `data/controller.log` and `data/encounters.sqlite3`. Use Open logs or Activity in the app.

Original AHK files and account data are preserved. Bundled launcher/account setup remains described in TESTING-v02.md; the v0.3 guide supersedes its fixed-resolution macro instructions.
