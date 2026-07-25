# FiinTrade Methodology — Architecture

## Directory Layout

```
C:\Users\Mr.D\Desktop\Phương Pháp Luận\
├── .git/
├── .github/
│   └── workflows/
│       └── ci.yml                    # JSON validation on push/PR to main
├── docs/
│   ├── FACTS.md                      # Project facts & constraints
│   ├── ARCHITECTURE.md               # This file — structure & relationships
│   └── SKILLS.md                     # AI-agent context & conventions
├── fiintrade_ranking-methodology_v1-0.md
├── fiintrade_ranking-methodology_v1-0.pdf
├── fiintrade_ranking-methodology_v1-0.json
├── fiintrade_scoring-methodology_v1-0.md
├── fiintrade_scoring-methodology_v1-0.pdf
├── fiintrade_scoring-methodology_v1-0.json
├── fiintrade_technical-analysis-methodology_v1-1.md
├── fiintrade_technical-analysis-methodology_v1-1.pdf
├── fiintrade_technical-analysis-methodology_v1-1.json
├── README.md
├── LICENSE                            # MIT
└── .gitignore
```

## File Relationships

- **`.md`** is the authoritative content source. Every edit goes here.
- **`.pdf`** is a rendered snapshot. Not tracked by Git (in `.gitignore`).
- **`.json`** mirrors the Markdown's section structure for programmatic use. Validated by CI.
- **`README.md`** indexes all three methodologies and links to the parent company.
- **`docs/`** holds AI-agent context that is not part of the public methodology content.

## CI Pipeline

1. Trigger: push or pull_request targeting `main`
2. Action: `python -m json.tool` on every `*.json` in the repo
3. Failure: workflow fails → PR blocked / push rejected
4. Recovery: fix JSON syntax and push again