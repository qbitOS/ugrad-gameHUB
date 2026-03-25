<!--
Principal: Tad R. Ericson · qbitOS / ugrad.ai
-->

# ugrad-gameHUB

**Principal:** [Tad R. Ericson](https://github.com/fornevercollective) · **qbitOS** / [ugrad.ai](https://ugrad.ai)

Org landing for the **μgrad games hub** — stable entry point and diligence-facing links. **Public live surfaces** use the **ugrad.ai** hosts below (Cloudflare Worker + static deploy); see [deployment notes](https://github.com/qbitOS/uvspeed/blob/main/docs/deployment/ugrad-games-subdomains.md) for operators.

## Live hub (ugrad.ai)

| Resource | URL |
|----------|-----|
| **Games hub** | [https://games.ugrad.ai/](https://games.ugrad.ai/) |
| **Raw corpus index** | [https://raw.games.ugrad.ai/](https://raw.games.ugrad.ai/) |
| **Go lab** (19×19 board, tensor slice) | [https://go.ugrad.ai/](https://go.ugrad.ai/) |
| **Terminal install** (benchmarks, `ugrad-cli`, sync) | [https://install.games.ugrad.ai/](https://install.games.ugrad.ai/) |

Shared assets (`quantum-theme.css`, `quantum-prefixes.js`, icons) resolve on the **`games.ugrad.ai`** origin via the Worker-backed static tree.

This repo’s **`index.html`** uses these **canonical** URLs only (no `github.io` / Pages preview links in the primary table).

## License & compliance

| File | Purpose |
|------|---------|
| [LICENSE](LICENSE) | **Apache-2.0** (org baseline; aligns with [qbitOS/qbitos-freya](https://github.com/qbitOS/qbitos-freya)) |
| [COMPLIANCE.qmd](COMPLIANCE.qmd) | Control envelope → [qbitOS/compliance](https://github.com/qbitOS/compliance) |
| [COMPLIANCE.md](COMPLIANCE.md) | IP, privacy, distribution |
| [ATTRIBUTION.md](ATTRIBUTION.md) | Authorship & AI tooling |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Contribution path |
| [SECURITY.md](SECURITY.md) | Reporting |
| [NOTICES.md](NOTICES.md) | Trademarks / upstream |

## Related

- [qbitOS/ugrad](https://github.com/qbitOS/ugrad) — μgrad org umbrella  

## Source (developers)

Implementation is maintained in **[qbitOS/uvspeed](https://github.com/qbitOS/uvspeed)** (`web/games-ugrad-hub.html`, shared `web/`). That link is for **contributors and operators**, not the public live hub table above.

---

*© Tad R. Ericson · qbitOS / ugrad.ai*
