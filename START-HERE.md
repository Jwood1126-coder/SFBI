# START HERE — the continuation document

*Written by the project's founding editor (Fable), 2026-07-07, for whoever holds this repository next: the author, a future model, or both. Everything below is load-bearing. Read this page, then go where it points.*

---

## What this repository is

One hundred science-fiction premises, dossiered in two volumes, being developed into books under a single system of law. One book is finished in draft: **THE GRAIN**, sixteen stories from the near present (2031–2044), compiled, audited, and published as draft one. Three more collections and a fifty-novel program are fully briefed and waiting. The system that built the first book — voice law, reality law, clarity law, the dyad test, the ration, the audits — is written down in full and applies to everything that follows. Nothing here requires the original editor. That is the point of this page.

## The estate, mapped

| Path | What it is |
|---|---|
| `ideas/volume-1-fifty-signals.html` | Volume I dossier — 50 novel-scale, far-future premises (Nº 01–50), each with synopsis and three-act skeleton. The seed bank for Project FAR. |
| `ideas/volume-2-fifty-mirrors.html` | Volume II dossier — 50 near-present premises (Nº 51–100). Sixteen became THE GRAIN; the other thirty-four are briefed for three planned collections. |
| `manuscript/BIBLE.md` | **The law.** THE GRAIN's constitution: book architecture (§1), the voice law with all amendments — reality, clarity, ration (§2), shared-world canon (§3), the working prompts (§4), sixteen chapter briefs with levers (§5). §2 governs every book in this estate unless a book's architecture doc amends it. |
| `manuscript/ATLAS.md` | The shelf: all 100 premises dispositioned (§B), GRAIN expansion briefs (§C), THE UNANSWERABLE briefs (§D), direction cards (§E–F), Project FAR — far voice, Novel Protocol, Tier A cards (§G), and the Brief Protocol (§H) for turning any premise into a brief. |
| `manuscript/atlas/` | Book-level architecture: one document per planned book (THE UNANSWERABLE, WHAT THE BODY KEEPS, ACREAGE) plus the FAR program doc. Each is that book's bible-§1: identity, arc, movements, range requirements, voice delta with calibration, canon posture, commission order, done criteria. |
| `manuscript/briefs/` | Commission-ready briefs: `body/` (11), `acreage/` (10), `far/` (Tier A novels, 10), `far-b/` (Tier B novels, 30), `far-c/` (Tier C novels, 10, each opening with its required conceptual repair). Every one of the 84 non-GRAIN premises has a full brief. |
| `manuscript/stories/` | THE GRAIN's sixteen chapters (`ch01`–`ch16`) plus `candidate-nameplate.md`, the commissioned "first things" story awaiting placement. |
| `manuscript/frame/` | Front matter, six part-openers, and `back.md` (cut from the compiled book by editorial decision; kept here). |
| `manuscript/the-grain.md` | The compiled book. **Generated** — never edit it directly; edit `stories/` and recompile (the cat-order is in CHANGELOG). |
| `manuscript/NAMES.md` | The name registry and collision law. Grep before naming anything. |
| `manuscript/EDIT-NOTES.md` | Every editorial pass on THE GRAIN: reader questions, fixes, accepted deviations, convergence tics, triage decisions. |
| `manuscript/CHANGELOG.md` | Dated record of every revision, with dyads per chapter and resume commands. Append one line per change, always. |
| `manuscript/AUDIT-COLD-READ.md` | The sixteen-story cold-reader audit, findings and defenses. |
| `manuscript/ACQUISITION-MEMO.md` | A zero-context editor's acquisition read of the compiled book. The structural critique that still needs answering (see Open Decisions). |

## The laws, in one breath each

1. **Voice law** (bible §2, rules 1–12): trade-locked imagery, no filtering, no epiphanies, banned phrases, numbers do the feeling.
2. **Reality law** (rules 13–16): real practice, real geography, real science; a professional in the trade must not flinch.
3. **Clarity law** (rules 17–20): orient inside the first page; the novum introduces itself plainly; **the function test** — trade texture may be *believed* unglossed, but anything the plot turns on must be *understood* before it bears weight. Ask: *if the reader skips this term, do they lose the ending?*
4. **The ration** (v1.5): signature constructions are budgeted ("the way…" ≤8 per story, one "the way a man—", no same-paragraph pairs). Run the phrase-frequency scan on every new draft.
5. **The dyad test** (v1.2): every story names its *equation* (hard constraint) and *mirror* (human bond) in one line each, logged in the changelog. Novels additionally name the *outward* and *inward* questions.
6. **One lever per revision.** Never two — you won't know which one moved the story.

## The audits (run all of them on every new draft, before acceptance)

Banned-phrase grep (list in bible §2 rule 8) · filtering-verb grep · name grep against NAMES.md and the corpus · prop grep (candy, seeds, scanners, pocket objects, notebooks) · phrase-frequency scan (any construction 5+ times across 5+ stories joins the ration) · a cold reader with zero context reconstructing the timeline · dyad named in the changelog. THE GRAIN's drafts that skipped none of these needed the fewest repairs.

## The author's laws (learned from Jacob directly — never regress on these)

- **Clarity over subtlety.** "I want the ideas to shine more than to impress a heavy reader's ability to pick up subtleties." Orient the reader on facts; keep mystery for meaning. Never respond by simplifying prose or cutting emotional subtext.
- **The function test is his.** So is the defect class *"a load-bearing word whose nearest meaning in context is the wrong one"* (machine→work equipment, trial→courtroom, phantom→ghost).
- **His ear finds what scans miss.** Both major post-draft laws (clarity, ration) came from his reading. When he says a passage confused or tired him, the passage is wrong — diagnose before defending, and defend only with evidence.

## State of play (2026-07-07) and open decisions

**THE GRAIN draft one is complete**: 16 stories, ~68,000 words, year-stamped 2031→2044, all audits passed, published to the author's artifact and pushed to GitHub. **Open, in order:** (1) the author's own front-to-back read; (2) placement of *Nameplate* (lean: Part IV, answering *Islanding*); (3) the Part I split — *Familiar*/*Because* are same-register adjacent, the memo's page-one critique; (4) the knife — whether *Deorbit* and *Adherence* stay (editor's recommendation: decide only after a full re-read with Nameplate placed); (5) the *Islanding*/*Absolution* oxygen-concentrator tableau — kept deliberately as a rhyme, the cold read heard repetition; author's call; (6) draft-two levers: ending-cadence variety (14 of 16 close on the freighted procedural gesture), the talisman-object and notebook repetitions. Then human beta readers, then copyedit. Publishing-path note: how this book was made requires disclosure on most channels; the author knows.

**Next books**: pick up the relevant architecture doc in `manuscript/atlas/`, follow its commission order, draft with bible §4 prompts under that book's voice delta, audit everything, log everything. For FAR novels: the Novel Protocol in ATLAS §G — treatment first, then arcs, then act-level revision.

## Working practice

Commit and push at every milestone — the author checks. Store deliverables in the repo, not in chat. Strong models draft; the strongest available model directs, close-reads, and makes the calls this page can't. When in doubt, reread bible §0 and the koan: **mysterious about what things mean is the book; mysterious about what things are is a defect.**

---

## HANDOFF — finishing the atlas deep-forge (written 2026-07-08, for any strong model)

A background workflow ("atlas-deep-forge") is forging full novel briefs for all 40 Tier B/C Volume I premises plus three book-architecture docs, a FAR program doc, and an audit of existing briefs. If it was interrupted, resume it in Claude Code with:
`Workflow({scriptPath: "/home/codespace/.claude/projects/-workspaces-SFBI/5f2f474e-8fc7-4384-bf05-0be47350e829/workflows/scripts/atlas-deep-forge-wf_bf9012d3-16b.js", resumeFromRunId: "wf_bf9012d3-16b"})` — completed agents replay from cache. (If that session directory is gone, the source premises live in the dossier HTML; re-derive per ATLAS §H.)

**When it completes, integrate (any model, ~30 minutes):**
1. Verify the estate: `manuscript/briefs/far-b/` has 30 files, `far-c/` has 10, `manuscript/atlas/` has 4 docs (unanswerable, body, acreage architectures + far-program).
2. Read the workflow's returned report (or `journal.jsonl` in the transcript dir): any brief with `pass:false` and unresolved problems gets fixed per its problem list; any file in the existing-brief audit's thin-list gets its missing element added per ATLAS §H.
3. Editorial spot-check, the one judgment step: read each brief's **Secretly about** and **Sibling rule** lines (grep them across far-b/ and far-c/). A good "secretly about" is a defensible editorial DECISION, not the logline restated. A good sibling rule names the genuinely closest premise. Rewrite weak ones; the Tier A cards in ATLAS §G are the calibration.
4. Update `manuscript/ATLAS.md`: §B and §G — Tier B changes from "hold" to "briefed — briefs/far-b/", Tier C from "reserve" to "briefed with repairs — briefs/far-c/"; add a §B line pointing at `manuscript/atlas/` for the book architectures.
5. Append a CHANGELOG line; commit everything; push. The author checks that things are pushed.
