# Compliance, IP, and public statements — ugrad-gameHUB

**Canonical baseline:** [COMPLIANCE.qmd](COMPLIANCE.qmd) (same structure as [qbitOS/qbitos-freya](https://github.com/qbitOS/qbitos-freya/blob/main/COMPLIANCE.qmd)) — compliance root, runtime path, control envelope.

This file adds **distribution** and **IP** detail for this static landing repo.

## License

- Files in this repository are licensed under the **Apache License 2.0** (see [`LICENSE`](LICENSE)). SPDX: `Apache-2.0`.

## Repository contents

This repository contains **only** static landing assets (`index.html`, documentation, and license text). The **μgrad games hub** application (registry, game shells, quantum stack) is built and maintained in the upstream **[qbitOS/uvspeed](https://github.com/qbitOS/uvspeed)** monorepo.

## Intellectual property

- **This repo**: Markdown, HTML, and `COMPLIANCE.qmd` in this repository are released under **Apache-2.0** unless noted.
- **Upstream apps**: Game UIs, `quantum-prefixes.js`, DAC/steno codecs, and other implementation code are governed by the **upstream repository’s** license and notices ([qbitOS/uvspeed](https://github.com/qbitOS/uvspeed)). Do not assume this repo grants additional rights over upstream code.
- **Trademarks**: **qbitOS**, **μgrad**, **uvspeed**, **beyondBINARY**, and third-party game or platform names may be trademarks of their respective owners. This project is **not sponsored or endorsed** by those owners. References to rule names (e.g. chess, go, cards) describe **abstract games**, not commercial products, unless explicitly stated otherwise.
- **No scraping / stock art claim**: This landing page does not embed third-party game artwork. Destinations linked from here may follow their own asset policies; see upstream [`docs/deployment/ugrad-games-subdomains.md`](https://github.com/qbitOS/uvspeed/blob/main/docs/deployment/ugrad-games-subdomains.md) and hub **IP & assets** copy in `games-ugrad-hub.html`.

## Privacy and data

- This static site does not run a backend. **No cookies** are set by `index.html` as shipped. Third-party sites (GitHub, Pages, upstream demos) have their own policies.
- **Telemetry**: If you use linked PWAs or terminals, refer to upstream documentation for `localStorage`, `BroadcastChannel`, and any future Worker/D1 ingestion.

## Enterprise / research use

- Static Pages **do not** provide a certified compliance package (SOC2, HIPAA, etc.). For governance expectations, see upstream **[ugrad enterprise readiness](https://github.com/qbitOS/uvspeed/blob/main/docs/ugrad-enterprise-readiness.md)**.

## Contact

For **this repo** (Pages, README, licensing): open an issue on **[qbitOS/ugrad-gameHUB](https://github.com/qbitOS/ugrad-gameHUB)**.  
For **game behavior, registry, or quantum stack**: prefer **[qbitOS/uvspeed](https://github.com/qbitOS/uvspeed)** issues or discussions.
