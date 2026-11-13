# Gendro releases

This repository holds only the release packages of Gendro (formerly Skyrim Wiki), a fan-made
Windows reference app for The Elder Scrolls V: Skyrim Special Edition with
Dawnguard, Hearthfire and Dragonborn. It contains no source code.

The app's built-in update check reads the release feed from this
repository over HTTPS. It sends no usage data and installs an update only
after you confirm it. Favorites and notes stay in `%LocalAppData%\SkyrimWiki`.

## Windows SmartScreen warning

The app is not code-signed. On first start Windows may show
"Windows protected your PC". Only run it if you downloaded the package
from this repository's Releases page. Then choose "More info" and
"Run anyway". Later updates through the built-in update check verify the
package checksum before installing.

## Licenses

- `LICENSE`: Apache License 2.0 for the application.
- `NOTICE`: attribution and trademark notice.
- `DATA_LICENSE`: how the catalog data may be used, including UESP
  attribution under CC BY-SA 2.5.
- `THIRD-PARTY-NOTICES`: packages and fonts shipped with the app.
- `OFL-Inter.txt`: SIL Open Font License for the Inter font.

Every release package contains these files as well.

Gendro is not affiliated with or endorsed by Bethesda Game Studios,
Bethesda Softworks or ZeniMax. The Elder Scrolls and Skyrim are trademarks
of their respective owners.
