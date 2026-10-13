# Olimem releases

Installers for Olimem desktop apps. Install them from **Olimem ERP**, which picks the right
file for your computer, checks it against `SHA256SUMS.txt` and installs it.

Each app's releases are tagged `<app>-v<version>`:

| App | Tag prefix | Files |
|---|---|---|
| Olimem Schools | `schools-v` | `olimem-schools-<version>-macos-universal.dmg`, `olimem-schools-<version>-windows-x64-setup.exe` |
| Olimem GIS | `gis-v` | `olimem-gis-<version>-macos-universal.dmg`, `olimem-gis-<version>-windows-x64-setup.exe` |

## App list

`launcher/apps.json` is the list of apps Olimem ERP shows. Every copy of Olimem ERP reads it when it
starts and on refresh, so adding an app here reaches everyone without a new build (GitHub may take up to
5 minutes to serve the change). Fields are documented in `olimem-launcher/src/types.ts`.

The installers are not yet code-signed. If you download one directly in a browser, macOS
Gatekeeper and Windows SmartScreen will warn about it; installing through Olimem ERP avoids the macOS warning.
