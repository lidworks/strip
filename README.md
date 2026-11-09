# Lidkeys / Strip — macOS releases

Lidkeys (installs as **Strip.app**) is a context-aware glass control strip for macOS 27 (Apple silicon).

- Product page: https://lidworks.github.io/lidkeys/
- Download the DMG from the [latest release](https://github.com/lidworks/strip/releases/latest).
- Support: lidworks@proton.me

## First launch (unsigned build)

This build is **not notarized** by Apple. macOS will warn on first launch. Either:

1. Open `Strip.app`. When macOS blocks it, click **Done** (not *Move to Trash*), then **System Settings → Privacy & Security → Open Anyway**, or
2. Terminal: `xattr -dr com.apple.quarantine /Applications/Strip.app`

Then grant Accessibility in System Settings → Privacy & Security → Accessibility.

7-day full trial. Buy a license at the product page; activate via menu bar → **Activate Pro…**.
