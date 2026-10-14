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
| `update.json` | Its version and checksum — frames verify both before installing |

Frames install an update only if it is signed with the same key as the app
already on them, so only releases published here by the author will install.

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
