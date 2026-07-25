# FiinTrade Methodology — AI Agent Skills

## Context Rules

1. **Language:** All methodology content is in Vietnamese. When answering questions about the content, use Vietnamese unless the user writes in English.
2. **Read-only by default:** Treat the `.md` and `.pdf` files as authoritative; do not rewrite them without explicit instruction.
3. **JSON validation:** Any `.json` file edit must pass `python -m json.tool` syntax validation. Run `python -m json.tool <file>` before committing.
4. **Commit messages:** Use Conventional Commits — `feat:`, `fix:`, `docs:`, `ci:`, `chore:` prefixes.
5. **No GPG signing:** Never attempt `-S` on commits.
6. **Licensing:** The repo is MIT licensed. Do not add proprietary headers.

## Common Workflows

### Validate JSON before commit
```powershell
python -m json.tool fiintrade_ranking-methodology_v1-0.json
if ($?) { git add . ; git commit -m "fix: ..."; git push }
```

### Review a methodology doc
Read the `.md` file with `Read` tool, then the `.json` for structure questions.

## Tooling
- **CI:** GitHub Actions (`.github/workflows/ci.yml`)
- **Git:** `gh` CLI authenticated as mrd-bdsmetro
- **OS:** Windows (PowerShell 5.1)
- **No external dependencies:** pure Markdown + JSON + Git