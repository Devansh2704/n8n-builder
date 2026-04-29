# n8n-builder

Production-ready starter assets to build the Prmpt.in outbound lead engine:

- `docs/lead-engine-setup.md` — end-to-end operating system.
- `workflows/prmpt-lead-engine.json` — importable n8n workflow scaffold.
- `templates/clay-columns.csv` — Clay table schema.
- `templates/clay-prompts.md` — reusable AI prompts for research + outreach.

## Quick start
1. Import `workflows/prmpt-lead-engine.json` into n8n.
2. Connect Airtable, Clay API, and Smartlead credentials.
3. Create a Clay table from `templates/clay-columns.csv`.
4. Use prompts in `templates/clay-prompts.md` for enrichment fields.
5. Follow the weekly rhythm in `docs/lead-engine-setup.md`.
