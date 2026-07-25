# FiinTrade Methodology — FACTS

## Project Identity
- **Product:** FiinTrade — financial technology platform by FiinGroup (formerly StoxPlus), est. 2008
- **Market:** Vietnamese stock exchanges (HOSE, HNX, UPCOM)
- **Audience:** Retail investors, advisors, brokers, traders
- **Parent company:** FiinGroup JSC

## Repository
- **URL:** `https://github.com/mrd-bdsmetro/FiinTrade-Methodology`
- **Visibility:** Public
- **License:** MIT (see `LICENSE`)
- **Default branch:** `main`
- **Remote:** `origin` → `github.com/mrd-bdsmetro/FiinTrade-Methodology.git`

## Documents
All methodology documents exist in three formats per topic:
- `.md` — Markdown source (the authoritative version)
- `.pdf` — Print/offline distribution
- `.json` — Structured layout data for rendering

| Topic | File prefix |
|---|---|
| Corporate Ranking | `fiintrade_ranking-methodology_v1-0` |
| Stock Scoring | `fiintrade_scoring-methodology_v1-0` |
| Technical Analysis | `fiintrade_technical-analysis-methodology_v1-1` |

## Language
All content is **Vietnamese**. Commit messages and CI config are in English.

## Infrastructure
- **CI:** `.github/workflows/ci.yml` — validates every `.json` file with `python -m json.tool` on push/PR to `main`
- **AI context:** `docs/` folder (`FACTS.md`, `ARCHITECTURE.md`, `SKILLS.md`)
- **`README.md`** — project entry point and file index

## Git Notes
- GPG signing is disabled (`commit.gpgsign false`)
- Working directory contains non-ASCII characters (`Phương Pháp Luận`)