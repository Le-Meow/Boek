# Manuscript revision plan — editorial audit before rewriting
**Date:** 27 October 2026  
**Status:** Proposed audit protocol, NOT approved manuscript alterations  
**Objective:** Give the author a stable, whole-book structure from which the remaining writing and editing can be finished, without losing good arguments, distinctive scenes or theology.

## 1. Editorial contract

The book must progress from the created man's mandate and relationship with God, through the fall, personal inheritance, contest for the heart, life under occupation and self-construction, to the false rule of the inner castle, Christ's victory, restored heart and name, and renewed `shamar` in the man's actual garden.

**No shortening target. No imposed chapter-length quotas. No mandate to flatten rich theological callbacks.** Editing should make the reader encounter development rather than the same premise being explained from scratch. Each proposed change must be tested against paragraph, chapter, book and reader experience.

The writer retains final authority. The agent is an editor, not a ghostwriter.

### Key distinctions

- **Re-establishing the fall**: explaining again what Genesis 3 already established without a substantial new insight. Candidate for compression.
- **Returning to the fall with a new dimension**: using Eden to illuminate a new aspect of the mandate, heart, enemy, occupation, self-rule, Christ's obedience or restored vocation. Usually valuable.
- **Productive motif**: a person, image or truth returns and *changes meaning* after the reader's intervening journey; do not eliminate the recurrence.
- **Redundant explanation**: the reader is made to retrace what is understood already merely to reach the chapter's new point.
- **Narrative pacing**: a strong scene may need less explanatory commentary afterwards; a difficult doctrine may need more, not less, before the next scene.

The previous suggestions to relocate **Cain** from Chapter 6 to Chapter 2, or **creation groaning** from Chapter 6 to Chapter 3, were challenged by the author and **retracted**. Do not treat them as decisions. Those moves require a new, book-wide argument if proposed again.

## 2. Source hierarchy and privacy

Read `editorial/CODEX_START.md` first. Establish final wording for Chapters 1–7 from the 27 October working text and Chapters 8–13 from V2. Consult the full master, Claude-assembled back half and V2 change record for provenance, omissions and previous structural decisions. Distinguish the current working text from archive versions.

**These source files may contain sensitive autobiographical content.** The GitHub repository is public. Keep sources in an untracked/local `sources/` directory for the audit. Do not commit sources or long personal quotations from those sources to public GitHub without explicit author approval. Reports in `editorial/reports/` should remain local or on a review branch with no private details until approved.

### Source integrity checks

- List all input filenames and SHA-256 checksums.
- Extract both document paragraphs and headings, preserving paragraph order; note DOCX coloured placeholders, footnotes, and formatting indicators separately where possible.
- Make stable source IDs such as `W27-CH06-P014` and `V2-CH11-P047`. State method and numbering clearly; do not pretend unstable PDF page numbers are universal IDs.
- Produce an inventory including epigraphs, citations, placeholder notes and author queries.
- Identify source-version conflicts, **without silently resolving** them.
- A proposed merger must account for **every** original paragraph: unchanged, reworded (future phase only), moved, consolidated, archived, or still unresolved.

## 3. The current 13-chapter arc — hypotheses to test, not reductive boxes

| Chapter | Primary development | Key continuity check |
|---|---|---|
| **1 Ground** | Creation, relationship, Adam's work and `shamar` under God's authority | The mandate is introduced clearly enough to grow across the book; avoid prematurely resolving restoration |
| **2 The Fracture** | Serpent's lie, breach, self-sufficiency, silence, fall and exile | Establish the first surrender strongly so future chapters can deepen it |
| **3 The Weight of Exile** | Lost home, ache, mortality, longing; Odysseus on Calypso's shore | Do not repeat its diagnosis of the ache later unless the later encounter transforms its significance |
| **4 The Boy** | Father/son presence, names, Telemachus, inherited verdicts and boyhood | Preserve this chapter's intimate, narrative depth; watch how its scenes pay off in 7, 11, 12, 13 |
| **5 The War for the Heart** | The heart as the guarded spring of life; God’s word, enemy’s attack and what is accepted within | Distinguish its spiritual claim from detailed internal mechanisms explored later in 8 |
| **6 Behaviour under occupation** | Two domains, occupied-yet-functioning life; Odysseus’ suitors, divided attention, Roman spectators | Do not strip its spiritual-war “meat”; avoid re-explaining Genesis each time it adds a new layer |
| **7 The Fallen Man's Forge** | Man's own contribution: bent iron/strengths, shame as fuel, false ambitions, hide/hustle/numb, approved religious mask | Contrast with Chapter 4 (wounds received) and Chapter 8 (rule beneath the constructed life); check whether contrast holds in the real text |
| **8 The Inner Castle** | Fortress, self-rule/false king, accusing shadow, false self and occupied interior | Check overlap with 5/7 on identity and shadow, but preserve the new architecture; track V2’s "Gates" ending |
| **9 The Door** | The rightful King approaches; man reaches the limit of self-repair; grace, repentance, surrender | Review gates opening **from within** (8) versus **from outside** (9); don't paper over the theological/imagistic tension |
| **10 It Is Written** | Christ as last Adam, the Word, cross, victory, authority and finished work | Check whether re-introductions of fall, throne, kneeling and King duplicate 8/9 rather than advance the case for Christ |
| **11 The Heart of Flesh** | New heart/Spirit/adoption; relationship restored; continuing strongholds; forgiveness and obedient response | Check pace from decisive divine action to ongoing healing/struggle; evaluate long sections for genuine steps, not loops |
| **12 The Name** | Received identity, distinct gifts/calling; wounds transformed into testimony and service | Track payoff of Chapter 4's naming and Chapter 7's forged identity; prevent generic wounds-as-weapons repetition |
| **13 Shamar** | The man returns to marriage, family, ordinary work, home, community and Kingdom under rightful rule | Pay off garden, father, son, Odysseus, time, word and presence without repeating the book’s thesis multiple times at the end |

This table is only an **organizing hypothesis**. Chapters may rightly perform more than one function. Do **not** strip an idea merely because it is not assigned to a chapter in the table.

## 4. Independent reviewers / subagents

All agents read the **entire selected manuscript**, not merely assigned chapters. Where Codex supports custom roles, use the project `.codex/agents/` definitions. Delegate separately; the integrating agent collects and reconciles their results.

**A. Architecture:** Map the argument's cause-and-effect progression through all thirteen chapters, and what each transition makes possible. Assess whether an idea is introduced too early, repeated without development, or postponed so long the reader lacks a premise. Recommend the *smallest* structural interventions.

**B. Motifs and repetition:** Track every significant return to Eden/the serpent/fall, `shamar`, garden, heart, false king/throne, father/name/son, iron/shards, darkness/light, Odysseus, occupation and King. Label occurrences as **NEW DIMENSION / CALLBACK / PAYOFF / RE-ESTABLISHMENT / REDUNDANCY / UNCERTAIN**. Explain *why*, using locatable passages and the intervening reader journey.

**C. Scripture/theology/quotation:** Test the flow of the argument against biblical passages and their contexts, separating textual claims from interpretation. Check source attribution (Homer, Juvenal, Augustine, historical scenes), and identify important distinctions, unsupported certainty or tension. Do not “correct” theology by silently substituting another tradition. Report only verifiable, material concerns, with references and confidence.

**D. Narrative and reader experience:** Assess where scenes carry the argument and where commentary repeats the scene's evident meaning; identify weak transitions, exhaustion, lost emotional momentum, artificial registers, unresolved planted motifs, scene placement and payoff.

**E. Preservation/provenance:** Account for every original chapter, paragraph, Scripture quotation, epigraph, coloured placeholder, note and important scene in all proposed changes. Detect material missing between the master, assembled back half and V2. Keep an exact recovery path and a loss-risk flag on every suggestion.

**Integrating editor:** Read all five independently produced findings. Resolve competing proposals or mark disagreement. Refuse any recommendation whose effect on earlier and later chapters is not assessed. Do not treat consensus as proof: quote textual evidence.

## 5. Audit procedure and gates

### Gate 0 — Verify, freeze and locate
Confirm the five source files and precedence. Record checksums and extract stable paragraph inventory. **If required inputs are unavailable, stop.** No reliance on the older repository book PDFs as replacements.

### Gate 1 — Read whole book and diagram argument
Create a 13-chapter map that explains exactly how the reader's understanding changes chapter to chapter. Document major scenes and planted/payoff motifs. No moves proposed yet.

### Gate 2 — Independent reviews
Five roles produce evidence-backed findings, covering every chapter and cross-chapter transitions. Compare V2 to the full master and Claude assembled source for unintentional losses.

### Gate 3 — Cross-examination
Challenge each candidate change with all five questions:

1. What exact point has the reader already understood, and *where*?
2. What **new theological, narrative or human reality** does the allegedly repeated passage add here?
3. What would be lost from the **original chapter** if altered?
4. Would removing/repositioning this damage a **later callback or ending**?
5. Is the best intervention **no change**, a short bridge, a single sentence trim, repositioning or a substantive addition?

Reject or downgrade findings that rely solely on similar terms, chapter titles or word counts.

### Gate 4 — Author approval
Publish **reports only**, with specific decisions requiring the author's judgement. No approved-by-silence changes. The author may preserve repetitions intentionally.

### Gate 5 — Revision after explicit approval (NOT authorised by this run)
Propose revisions chapter by chapter, with a source-aligned patch and reversible ledger. After each chapter, check how the entire book reads and that every motif and promise remains. Only then carry out a voice/style pass.

## 6. Required deliverables (files under editorial/reports/)

1. `00_source_register.md` — exact versions, filenames, hashes, source authority, chapter boundaries, placeholder handling and any missing files.
2. `01_whole_book_spine.md` — reader's journey and what each chapter adds, with linkages between 2–7 and 8–13.
3. `02_repetition_motif_ledger.csv` — columns: `motif,source_id,chapter,opening_words,earlier_source_id,later_source_id,classification,new_function,evidence,verdict,confidence,downstream_payoff`.
4. `03_theology_and_attribution_flags.md` — concrete references, issue, consequence, confidence; flag rather than silently resolve.
5. `04_narrative_reader_journey.md` — scenes, pace, narrative payoff, risk of reader fatigue and lost tension.
6. `05_preservation_register.csv` — `source_id,source_version,chapter,opening_words,placeholder_or_epigraph,current_status,proposal_id,exact_preservation_location,risk`. For phase 1, statuses will mostly be `UNCHANGED` or `PROPOSED_ONLY`.
7. `06_editorial_decision_map.md` — **one consolidated author-facing report** organised by chapter; **KEEP / CONDENSE / MOVE / EXPAND / REMOVE**, evidence, dependencies, estimated impact, dispute notes, priority `ESSENTIAL / WORTHWHILE / OPTIONAL`, and approval status `PENDING`.
8. `07_author_decisions.md` — concise questions that genuinely require author judgement, with options and trade-offs; keep to material decisions only.

Quote snippets briefly in any report intended for public GitHub; keep the full preservation table and personal-text excerpts **local**.

## 7. How to justify a revision proposal

A proposed change must be recorded like this:

- **Proposal ID:** R-CH06-001
- **Source:** exact file + ID + opening words (no invented citation)
- **Problem:** what the reader is made to retrace
- **Evidence:** earlier scene/argument and later callback; explain if these differ
- **New contribution at this location:** what is essential and must survive
- **Proposal:** KEEP / CONDENSE / MOVE / EXPAND / REMOVE; cite exact paragraphs
- **Original chapter impact:** what's lost and how it is replaced or preserved
- **Destination/other chapters impact:** transitions, sequence, repetition and payoff
- **Preservation:** original intact, exact content archived and recoverable
- **Counterargument:** best reason to leave it exactly where it is
- **Risk/confidence:** theological, narrative, authorial, version-provenance
- **Approval:** PENDING unless author approves specific proposal

**Default is KEEP until a stronger alternative survives scrutiny.** This is not a proofreading or generic concision exercise.

## 8. Known high-value tests, not pre-decided edits

- **Chapters 2–7:** Does each return to Genesis disclose a new level? Is the opening of Chapter 6 carrying indispensable teaching about the two domains while occasionally repeating the entire story of the fall?
- **4 → 5 → 7 → 8:** Distinguish wounds and names received, the heart as contested ground, self-forging from wounded strengths, and the shadow/false rule. Find *actual* crossings, rather than assign fixed doctrinal ownership.
- **6 → 8 → 9 → 13:** Odysseus’ occupied household as a planted image, the castle under a wrong banner, the rightful King's coming, the restoration of home, wife, son and land. Test narrative escalation and payoff.
- **7 → 8:** Does the forge end after showing construction of the false identity while the castle opens a genuinely new inquiry into government/allegiance? Or do the two chapters re-explain each other?
- **8 → 9:** Inside/outside gates; theological consistency without flattening different aspects of grace and human response.
- **9 → 10 → 11:** Is the cross itself allowed to be decisive, or do these chapters repeat the surrender/throne argument rather than reveal Christ, the new heart and its consequences?
- **11 → 12 → 13:** Name, healing, gifts, forgiveness and ordinary household mission must each provide a new step. Test whether Chapter 13 gives several overlapping endings or a cumulative conclusion.
- **Across all chapters:** Protect the narrator's family scenes, boyhood pool, father on shoulders, personal account of the forge and recovery, Mr Cooper, sister placeholder, Homeric images, and the returning garden. Do not force every image to recur if the recurrence achieves no purpose.
- **V2 placeholders:** Do not mistake a working note for finished prose or delete one because it appears awkward inside the draft.

## 9. Work completion criterion

The job is complete when the author has a credible **whole-book editorial map**, can tell what is genuinely left to write, can see every proposed structural intervention with evidence and downstream impact, and can trust that **nothing worth keeping will disappear through an unrecorded AI edit**.

The phase-1 job is **not complete** if only the first seven chapters were reviewed, if later chapters are taken from the old full master instead of V2, or if the original manuscript has been rewritten without review.
