# Licenses

## Rinse code

Copyright © 2026 Mikalai Kushner. All rights reserved. Licensed under the
[Rinse Source License](LICENSE).

Only Mikalai Kushner may sell Rinse or offer it in an app store. Anyone
else may build it for personal, non-commercial use, and may not sell it.

The name "Rinse" and the Rinse icon (`App/Assets.xcassets/AppIcon.appiconset/`,
`Extensions/YouTube/Resources/icon-*.png`, `scripts/make-icons.swift`) are
not licensed. Forks must use their own name and icon.

On 4 November 2026 this project stopped being offered under GPL-3.0. Copies
already received under the GPL keep the rights that license gave for those
copies.

## Third-party filter lists

Rinse's content blockers are compiled from these lists (see `filters/sources.json`).
Rules are converted to Safari's format by `tools/filters/compile.py`; unsupported
rules are dropped.

These lists are not part of the Rinse Source License. The compiled
`Extensions/Blockers/*/blockerList.json` files contain rules derived from them,
and those rules stay under the lists' own licenses, with attribution. Other
people may still use these lists under those licenses, including in a product
they sell.

| List | Source | License |
|---|---|---|
| EasyList | https://easylist.to | GPL-3.0 or CC BY-SA 3.0 (we use CC BY-SA 3.0) |
| EasyPrivacy | https://easylist.to | GPL-3.0 or CC BY-SA 3.0 (we use CC BY-SA 3.0) |
| RU AdList | https://forums.lanik.us/viewforum.php?f=102 | CC BY 3.0 |
| Rinse's own rules (`filters/rinse.txt`) | this repository | Rinse Source License |

Thanks to the EasyList and RU AdList authors and contributors.
Attribution for EasyList and EasyPrivacy: "The EasyList authors (https://easylist.to/)".
