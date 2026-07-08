# THE NAME REGISTRY — collision policy and roster
### Added 2026-07-07 after an external reader caught recycled names across the dossiers. The audit confirmed it; the fixes are logged in CHANGELOG. This file is the standing control.

## Policy (binding for all drafting and revision)

1. **Full names are unique across the entire corpus** — both dossiers, all books, all briefs. No exceptions.
2. **Given names of protagonists and POV characters are unique across the corpus.** Secondary characters may repeat a given name across *different* volumes, never within one book.
3. **Vessels, stations, companies, drugs, and institutions are unique across the corpus.** These are proper nouns readers track harder than people.
4. **Surnames may repeat across volumes** for unrelated characters (the world reuses surnames; two unrelated Okafors in different books is realism, not error) — but never within one book.
5. **Before naming anything in a new draft or revision, grep the corpus:**
   `grep -rio "NAME" ideas/ manuscript/stories/ manuscript/frame/ | wc -l` — zero hits or a deliberate, logged exception.

## Names with one owner (settled by the 2026-07-07 de-duplication)

- **Marisol Vega** → Vol II Nº58 *The Bar* (bar pilot). Vol I Nº15's astrophysicist is now **Carmen Alarcón**.
- **Amara** → Vol I Nº03 (Ijeoma). Nº48 is now **Mei Chen**; Vol II Nº71 is now **Awa Diallo**.
- **Dana** → Vol I Nº05 (Voss). Nº45 is now **Constance Whitfield**.
- **Ezra** → Vol II Nº55 (Stern). Vol I Nº43 is now **Asa Nakamura**.
- **Tomás** → Vol II Nº57 / book ch. 7's world (Aguilar). Vol I Nº23 is now **Ezequiel Reyes**.
- **Iris** → Vol II Nº83 (Blevins). Vol I Nº22 is now **Noemi Castillo**.
- **Wren** → Vol II Nº69 (Adeyemi — canon; the Signature bears her name). Vol I Nº40 is now **Tayo Aluko**.
- **Lena** → Vol II Nº94 (Faber). Vol I Nº11 is now **Zora Okafor**.
- **Priya (dossiers)** → none; Vol I Nº13 is now **Sarita Ramanathan**. Book usage: see queue below.
- **Halcyon** → THE GRAIN ch. 6 (the orbital platform). Vol I Nº10's ship is now **Providence**; Nº37's consortium is now **Cirrus**.
- **Meridian** → THE GRAIN ch. 7 (the deorbited station). Vol I Nº44's generation ship is now **Lodestar** (rule 3, vessels unique; 2026-07-08). The book's dossier title *Parallax* is unaffected — the collision was the ship name only, not the title, which stands.
- **Theo (Vol II)** → Nº66 (Bess's son). Nº51's husband is now **Emil**. The book's Theo Lund (ch. 5) stands — different volume, secondary character, allowed under rule 2.

## Queued in-book fixes — apply AFTER the clarity pass closes (files are in revision; do not edit while agents hold them)

- **ch05**: *Dale Aune* → **Merle Aune** (collides with ch07's CAPCOM Dale, same book).
- **ch05**: the group-chat *Priya* → **Ruchi** (collides with ch07's Priya Menon, same book).
- Then re-run the policy-5 grep for: Dale, Priya, Merle, Ruchi.

## Known allowed repeats (logged exceptions, rule 4)

- Okafor: Vol I Nº11 (Zora) / Vol II Nº68 (Nell) — different volumes, unrelated.
- Halvorsen: Vol I Nº27 (Enna) / Vol II Nº64 (Marit) — different volumes, unrelated.
- Reyes: Vol I Nº23 (Ezequiel), Nº41 (Alma) — same volume, both dossier-only, unrelated; watch if either is developed.
- Noor: ch06 given-name-as-surname (Noor Haddad) vs Vol II Nº100 surname (Hafsa Noor) — different positions, allowed.
- Anand: Vol I Nº44 surname (Suli Anand) vs Vol I Nº36 given name (Anand Chaudhary, Mars premise) — different positions, both dossier-only, unrelated; allowed under the Noor precedent (2026-07-08).

## Nameplate (candidate, 2026-07-07)
- **Tess Ames** (protagonist) — unique corpus-wide. Drafter's first choice "Cass" correctly rejected (Cass Voss, Vol II Nº premise); "Marta" correctly rejected (Marta Ellingson, ch05).
- **Ruben Ochoa** — clear (only "rubens" hit is *Picea rubens*, ch10, a tree).
- **Ramona Ybarra** — clear.
- **Krider, Harney County, OR** (invented town, off OR-78, 38 mi SE of Burns) — clear; real neighbors (Crane, Burns) used only as geography.
- Props registered: wall-marker ledger, Ameraucana eggs, blue heeler, seedling heat mat, soft-start box, dual-fuel generator, juniper firewood.

## Project FAR briefs — naming state (2026-07-08)
All 40 Tier B/C briefs carry a Registry field; the forge's inline fix-stages resolved the major collisions at write time (e.g. Nº03 renamed off *Silas Okoro*; Nº20 off *Idris/Noor El-Amin*; Nº41 *Alma Reyes*→*Alma Sandoval*; Nº18 *Imre Kass*→*Aurel Kass*). Only Nº37 uses the surname *Okoro* as a live character; other files merely cite it.
**Known residue, resolve at commission time (protocol re-greps before any novel is drafted):** the given name *Idris* recurs on three secondary characters across separate novels (Bello Nº48, Okoro Nº37, Kane Nº41 — full names distinct, none the sole protagonist; within policy but reduce if two are developed near each other); the surname *Reyes* appears on Vol I FAR protagonists in Nº01 (*Sana Reyes*, pre-existing Tier A) and Nº23 (*Ezequiel Reyes*) — a within-volume surname repeat to break when the second of the two is commissioned. Registry citation lines inside a few briefs still reference pre-fix hit counts; treat the brief's *chosen* name as authoritative and re-verify by grep at development time.
