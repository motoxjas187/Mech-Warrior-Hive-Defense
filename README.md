# Mech Siege: Hive War

An idle mech defense game for Android: a 12,000-weapon draft pool (10 bases × 20 prefixes × 5 elements × 12 suffixes, choose 1 of 2 on every new hardpoint or Weapon Cache), six hardpoints, squad-based alien waves, Hives, Queen bosses, an upgrade tree, fusable modules and Core Reboot prestige.

## Get the APK
Every push to `main` builds a new APK automatically.
- **Latest download:** https://github.com/motoxjas187/Mech-Warrior-Hive-Defense/releases/latest
- Open the `.apk` on your phone and allow "Install unknown apps" if asked.

## Project layout
- `www/index.html` — the whole game (HTML/JS canvas). Edit this to change gameplay.
- `app/` — the small Android WebView wrapper that loads the game.
- `.github/workflows/build-apk.yml` — builds and publishes the APK.

## Notes
- The APK is signed with a debug key for testing. A real release keystore is needed before uploading to Google Play.
- Saves are stored on the device (WebView localStorage).
