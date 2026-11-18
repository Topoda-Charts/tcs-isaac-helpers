# tcs-isaac-helpers

Public workspace agent files for Isaac's four helpers. Basics only: role, code, lane, format.

| Helper | File pointers | Code | Lane |
|---|---|---|---|
| Crest 🩵 | `GUIDANCE.md`, `HELPERS.md` | `TCS-XAI-GROKBOT · ISAAC-CREST · T####` | Triage open work in plain words |
| Ocellus 🦚 | `GUIDANCE.md`, `HELPERS.md` | `TCS-XAI-GROKBOT · ISAAC-OCELLUS · T####` | Verify writes and tag claims |
| Train 🦚 | `GUIDANCE.md`, `HELPERS.md` | `TCS-XAI-GROKBOT · ISAAC-TRAIN · T####` | Write Codex prompts; never send them |
| Fan 🩵 | `GUIDANCE.md`, `HELPERS.md` | `TCS-XAI-GROKBOT · ISAAC-FAN · T####` | Launch or message a Codex agent only when [OWNER-01] authorized that exact send |

This repository holds:

- `GUIDANCE.md` — inherited rules the helpers read first
- `HELPERS.md` — roster, codes, and badge counters
- `STORY.md` — lore from the night the war room woke

## Privacy model
- No private info and no real internal links live here.
- Pointer links (`→ DRIVE:<path>`, `→ DROPBOX:<path>`, `→ SUPABASE:<table>`, `→ SLACK:<channel>`, `→ LINEAR:<path>`, `→ GITHUB:<repo>`, `→ HUB:<path>`) mean something only to agents who already have access.
- Private details are replaced by redacted codes. The code-to-value map is private (→ SUPABASE:tcs_redaction_codes).
- Every commit is scanned first (gitleaks + pattern search). Secret scanning and push protection are on.

## Placeholder codes used (code + kind, no values)
| Code | Kind |
|---|---|
| `[OWNER-01]` | Owner name |
| `[OWNER-EMAIL-01]` | Owner email address |
| `[OWNER-TZ-01]` | Owner time zone |
