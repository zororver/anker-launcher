# Anker Launcher

Downloads for Anker Launcher, the desktop app for [AnkerGames](https://ankergames.net).
Get the latest version from the [Releases](../../releases/latest) page.

- Windows: `AnkerLauncher-win-Setup.exe` (installer) or `AnkerLauncher-win-Portable.zip`
- Linux: `AnkerLauncher-<version>-x86_64.AppImage`

Updates are signed; the launcher verifies every update before installing it.

## Third-party software

The launcher ships [aria2](https://aria2.github.io/) (GPL-2.0-or-later with the OpenSSL exception) as a separate program, and [ludusavi](https://github.com/mtkennerly/ludusavi) (MIT). The complete source of the exact aria2 in each release is attached to that release:

- Windows: `aria2-<version>.tar.xz`, the aria2 project's own source for its Windows build
- Linux: `aria2_<version>.dsc` and the files it lists, Ubuntu 22.04's source package

`THIRD-PARTY-NOTICES.txt`, installed beside the launcher, lists every component and its licence. You can also ask for any of this source through [ankergames.net/contact](https://ankergames.net/contact).
