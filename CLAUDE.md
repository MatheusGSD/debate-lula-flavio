# Lula × Flávio: análise de debates

Painel estático em `docs/` (GitHub Pages); pipeline em `scripts/`, prompts em `prompts/`. Ver `README.md`.

## Agent skills

### Issue tracker

Issues e specs ficam como markdown local em `.scratch/<feature>/`. See `agents/issue-tracker.md`.

### Triage labels

Os cinco rótulos padrão (`needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`), como linha `Status:` em cada arquivo. See `agents/triage-labels.md`.

### Domain docs

Single-context: `GLOSSARY.md` na raiz e ADRs em `agents/adr/` (fora de `docs/`, que é publicado). See `agents/domain.md`.
