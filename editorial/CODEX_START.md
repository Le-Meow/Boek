# Start here: manuscript structural audit

**You do not have access to the ChatGPT conversation. This repository file is the handoff.** Use the linked author-context note as a working summary of the conversation, not as a verbatim full transcript.

## First, locate these inputs in the local workspace

| Source file | Role |
|---|---|
| `sources/01_latest_working_manuscript_2026-10-27.txt` | **Preferred latest wording for Chapters 1–7**, subject to confirming where chapter boundaries fall. It also contains older Chapters 8–13; do not use those later chapters as the final version. |
| `sources/02_chapters_8-13_V2.docx` | **Preferred current structural wording for Chapters 8–13** (V2). |
| `sources/03_current_full_master_with_placeholders.docx` | Full pre-V2 manuscript and formatting/placeholder comparison; consult for wording provenance, context and losses. |
| `sources/04_claude_back_half_assembled.docx` | Earlier condensed structural reference for Chapters 8–13; **not** the authoritative later text. |
| `sources/05_V2_editorial_change_record.md` | Excluded/merged passage archive and prior structural decision ledger; check against V2. |

The repository already contains `Book 1.pdf` and `Book 2.pdf`, but these must be treated as **unverified older sources**, not substitutions for the above.

If an author has supplied a newer exact passage since the source snapshot, flag a version conflict rather than silently choosing one.

## Task to run now

1. Confirm all five sources, identify chapter boundaries and compare overlapping versions.
2. Create a source register and stable IDs for every paragraph in the selected working text; record all placeholder notes separately.
3. Read all 13 chapters **before making relocation or cutting recommendations**.
4. Run independent agents: architecture; motif/repetition; Scripture and theology; narrative/reader journey; preservation and paragraph accounting. If agents unavailable, do labelled independent passes sequentially.
5. Cross-examine disagreements. Do not hide conflicting recommendations.
6. Write the deliverables specified in `editorial/REVISION_PLAN.md`, **without modifying the manuscript**.
7. Finish with a concise author-facing decision brief: what is sound, what is genuinely circular, what may be missing, the smallest viable set of changes, and author decisions required.

## Paste-ready first message for Codex

> Read AGENTS.md, editorial/CODEX_START.md, editorial/REVISION_PLAN.md and editorial/chat-context-2026-10-27.md. This is phase 1 of a 13-chapter book editorial audit. The full ChatGPT discussion is NOT available to you; the author-context file contains the essential corrections and priorities. Verify the five source files in sources/; if absent tell me exactly which are missing and STOP rather than using older Book PDFs. If present, delegate independent structural, motif, theological, reader-journey and preservation audits to separate agents. Review the entire book before recommending moves or cuts. Do NOT rewrite or change manuscript files. Produce the report and preservation ledger specified in REVISION_PLAN.md. An Eden reference that reveals a new dimension must not be mistaken for needless repetition. Distinguish the author's words from earlier AI drafts, and preserve every exact source passage.

**Success at this stage means a dependable editorial roadmap, not more prose.**
