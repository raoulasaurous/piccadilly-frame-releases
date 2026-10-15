# Tube Board — Releases

Official software updates for **Tube Board** picture frames.

This repository contains only the finished app. Frames check here automatically
once a night and install updates on their own — no action needed. You can also
check by hand on the frame: tap the board, tap the cog, then **About → Check for
updates**.

Each release contains:

| File | Purpose |
|---|---|
| `piccadilly-frame.apk` | The app |
| `update.json` | The app's version and checksum. Frames verify both before installing |
| `page.zip` | The board's page |
| `page.json` | The page's version, checksum and signature. Frames verify all three before switching to the page |

Frames install an update only if it is signed with the same key as the app
already on them, so only releases published here by the author will install.
A new page is also checked on the frame. If it does not work, the frame goes
back to the page it had before.

## License

Copyright © 2026 Raoul Woodruff & Lockline Studio LTD. All rights reserved.

This software is provided solely for updating genuine Tube Board frames.
Copying, redistribution, modification, or installation on other hardware is
not permitted. No license, express or implied, is granted by the availability
of these files.

## Data and third-party components

- Powered by TfL Open Data. Contains OS data © Crown copyright and database
  rights 2016 and Geomni UK Map data © and database rights [2019].
- National Rail departures: Powered by National Rail Enquiries. Data provided
  under licence through the Rail Data Marketplace.
- DejaVu Sans fonts: Bitstream Vera and DejaVu licence.
