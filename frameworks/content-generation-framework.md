# Content Generation Framework

A three-stage workflow for producing brand content with AI in the loop — designed so the human judgment lands where it matters most.

---

## The three stages

### 1 · Brief (human owns)

Never start from a blank page *inside* the AI conversation. Start from a completed brief:

- **One-line thesis** — what must the reader believe or do afterwards?
- **Audience state** — what do they already know, assume, and feel?
- **Format & constraints** — length, channel, what it must not sound like.

*Output: 5–8 lines of brief. If you can't write the thesis line, the idea isn't ready — go back to ideation.*

### 2 · Generate (AI owns volume)

Work in two passes, never one:

- **Pass A — angles.** Ask for 10 distinct angles on the thesis, one line each. Pick 2. Do not draft yet.
- **Pass B — drafts.** For each chosen angle, request a full draft under the brand-voice prompt (see `brand-voice/prompt-template.md`).

*Why two passes: single-pass generation produces "acceptable first idea" content. The angle pass is where originality actually comes from.*

### 3 · Edit (human owns)

Edit against three gates, in order:

| Gate | Question | Action if failed |
|---|---|---|
| **Truth** | Is every claim verifiably true? | Cut or verify — never "fix" tone over facts |
| **Voice** | Would the brand's best writer have written this line? | Rewrite the line, not the paragraph |
| **Point** | Does the thesis line survive? | Cut anything that doesn't serve it |

**Rule of thumb:** if more than ~40% of the draft survives to publication untouched, the brief was too vague.

---

## What this framework prevents

- Generic "AI-smell" output (fixed by the angle pass + voice prompt)
- Volume without thesis (fixed by the brief stage)
- Over-polished drafts that say nothing (fixed by the Point gate)
