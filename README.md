# Olimem releases

Installers for Olimem desktop apps. Install them from **Olimem ERP**, which picks the right
file for your computer, checks it against `SHA256SUMS.txt` and installs it.

Each app's releases are tagged `<app>-v<version>`:

| App | Tag prefix | Files |
|---|---|---|
| Olimem Schools | `schools-v` | `olimem-schools-<version>-macos-universal.dmg`, `olimem-schools-<version>-windows-x64-setup.exe` |

The installers are not yet code-signed. If you download one directly in a browser, macOS
Gatekeeper and Windows SmartScreen will warn about it; installing through Olimem ERP avoids the macOS warning.
