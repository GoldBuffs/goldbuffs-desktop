# Gold Buffs — Desktop App

The Gold Buffs desktop app for gym owners and staff — a native macOS/Windows app around the same
dashboard you'd use in a browser at `goldbuffs.com`, with a couple of real desktop-app advantages:
it opens instantly (no browser tabs, no typing a URL), and it checks for updates on its own.

**This repo holds built installers only — no source code.** It exists so releases can be public
(and update checks need no login) while the app's actual source stays in a private repo.

**Who this is for:** gym owners and staff only. There's no System Console / system-owner access
in this app.

## Install

### macOS

1. Download the latest `Gold Buffs-<version>.dmg` from the [Releases page](../../releases).
2. Open the `.dmg` and drag **Gold Buffs** into your **Applications** folder.
3. Launch it from Applications (or Spotlight). The first time, macOS will warn that it's from an
   "unidentified developer" — right-click (or Control-click) the app → **Open** → **Open** again
   in the confirmation dialog. You only need to do this once.

### Windows

1. Download the latest `Gold Buffs Setup <version>.exe` from the [Releases page](../../releases).
2. Run it. It's a one-click installer — no wizard, no admin prompt (it installs just for your
   Windows user account) — it installs and launches automatically.
3. Windows SmartScreen will likely warn "Windows protected your PC" the first time, since the
   installer isn't code-signed yet. Click **More info** → **Run anyway** to proceed.

## Updating

The app checks for updates automatically (on launch, and periodically while it's open). When a
new version is available, it'll ask before downloading, then ask again before restarting to
install — it never updates or restarts without asking first. You can also just re-download and
reinstall from the Releases page at any time.

## Signing

Neither build is code-signed yet (that needs a paid Apple Developer account / Windows code-signing
certificate) — the warnings above are expected, not a sign anything's wrong.
