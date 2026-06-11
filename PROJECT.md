# PROJECT — Worship Pop-Punk Album (handoff / continuation doc)

> **Purpose:** single pickup point so you can `git pull` on your PC and keep going. This indexes every
> track, the Suno formatting rules we locked in, the running order, and what's still open. Each song lives
> in its own `.md` with a copy-paste **"⬇️ Ready to Drop Into Suno (Custom Mode)"** block (Title / Style /
> Exclude / Lyrics).

**Branch:** `claude/canadian-campfire-song-87x8lh`
**Last updated:** 2026-06-11

---

## What's in this repo

Two separate projects:

1. **Worship pop-punk album** — 12 tracks (Good Charlotte / Boys Like Girls / Red Jumpsuit Apparatus
   energy; Christ-centered; conviction + hope, never shaming). *This is the active project.*
2. **Canadian campfire songs** (earlier, unrelated): `one-more-log-on-the-fire.md`,
   `fireside-anthem-radio-edit.md`, `fireside-anthem-confession-style.md`.

---

## The Album — track index

Each row → its own file. "Role" = where it sits emotionally. All style boxes are ≤200 chars (Suno cap).

| # (story) | Title | File | Theme / scripture root | Style — BPM/key | Energy |
|---|---|---|---|---|---|
| 1 | **Lovers of the Light** | `lovers-of-the-light-worship-punk.md` | Won't conform, hope for all — 2 Tim 3, John 3:17 | Emotive post-hardcore, 165, D | Anthem (dual-gtr, breakdown) |
| 2 | **Ever Learning** | `ever-learning-worship-punk.md` | Last-days deception, don't be fooled — 2 Tim 3:7, Dan 12:4 | Intimate building, 140, E | Quiet→cathartic warning |
| 3 | **Anchor (Holding On to You)** | `anchor-worship-punk.md` | Hold on when it shakes — Heb 6:19, Ps 46 | Fast skate-punk, 184, D | Fast/aggressive |
| 4 | **I Don't Know (But You Do)** | `trust-you-worship-punk.md` | Trust the unknown future — Prov 3:5-6, Heb 11:8 | Bright radio pop-punk, 160, A | Upbeat/bouncy |
| 5 | **Still (Be Still)** | `be-still-worship-punk.md` | Peace in the storm — Ps 46:10, Mark 4:39 | Melodic emo, 144, G | Mid/melodic (BLG) |
| 6 | **It Is Finished** | `it-is-finished-worship-punk.md` | The cross, 3rd-person witness — John 19:30, Isa 53 | Raw cry-out lament, 124, Bm→D | Heavy, slow, cry-out |
| 7 | **Empty (All I Need)** | `empty-all-i-need-worship-punk.md` | Found by grace from vice — John 4, Luke 15, Ps 23 | Piano ballad that explodes, 130, D | Heart-wrench build |
| 8 | **Under (Came Up New)** | `under-baptism-worship-punk.md` | Baptism, buried & raised — Rom 6:4, Col 2:12 | Atmospheric post-rock, 150, C | Heart-wrench build |
| 9 | **Off the Fence** | `off-the-fence-worship-punk.md` | Altar call — 1 Kings 18:21, 2 Cor 6:2, Rev 3:20 | Gospel-tinged pop-punk, 150, G | Warm invitation |
| 10 | **Take It All** | `take-it-all-worship-punk.md` | Surrender & adore — Rom 12:1, Rev 5:12 | Emotive worship, 138, C | Intimate→huge worship |
| 11 | **Kept the Faith** | `kept-the-faith-worship-punk.md` | Endure to the end — 2 Tim 4:7, Heb 12:1 | Driving punk-rock singalong, 152, D | Communal crowd-chant |
| 12 | **Already Won** | `already-won-worship-punk.md` | Victory / He returns — 1 Cor 15:55, Rom 8:37, Rev 21 | Triumphant pop-punk, 172, E | Biggest finale (reprises hooks) |

**Narrative arc:** the world (1–2) → the struggle (3–5) → the cross (6) → the rescue (7–8) → the call (9)
→ the response (10–11) → the victory (12).

---

## Suggested running order (paced for dynamics)

The index # above *is* a workable story order, but for loud/quiet pacing on the record:

1. Lovers of the Light *(statement opener, anthem)*
2. Anchor *(fast, hits hard early)*
3. I Don't Know (But You Do) *(bright lift)*
4. Ever Learning *(first intimate breath / warning)*
5. Still (Be Still) *(melodic mid)*
6. **It Is Finished** *(the gospel center — heaviest, slowest)*
7. Empty (All I Need) *(rescue, builds back up)*
8. Under (Came Up New) *(rescue, atmospheric)*
9. Off the Fence *(altar call, warm)*
10. Take It All *(surrender, intimate→huge)*
11. Kept the Faith *(communal, fists-up)*
12. **Already Won** *(triumphant closer; outro reprises earlier hooks → album bow)*

---

## Suno formatting cheat-sheet (rules we locked in)

**Style of Music box**
- **~200 char hard cap** — Suno silently truncates past it. (Every track here is verified ≤200.)
- Comma-separated descriptors, **genre first**, weights early terms heaviest.
- Order: genre → 1–3 instruments → **BPM as a number** → vocal (character/delivery/register) → mood.
- 5–8 tags is the sweet spot. **No artist names** (filtered) — describe the *sound* instead.

**Lyrics box**
- **~3,000 char cap** (also silent truncation). All tracks are under it.
- `[Section]` tags: `[Intro] [Verse 1] [Pre-Chorus] [Chorus] [Bridge] [Final Chorus] [Outro]`.
- `(parentheses)` = backing vocals / ad-libs / **performance & dynamic direction** (e.g.
  `(quiet, intimate)`, `(full band, cathartic)`, `(gang vocals)`).

**Title box:** 80 char cap.

**⚠️ The country trap (learned the hard way on "Kept the Faith"):**
- Positive style words **override** the Exclude box. Putting *folk-punk, mandolin, banjo, acoustic,
  jangly, raspy, heartland, twang, lighters-up* in the style box makes Suno build a country song **even
  if "country" is in Exclude.**
- To force punk: lead with **"punk rock / pop-punk / distorted power chords / punk drums / gang vocals"**
  and exclude `country, Americana, folk, bluegrass, mandolin, banjo, acoustic, twang`.
- Same caution for **"Off the Fence"** — its `hammond organ + tambourine + choir` can lean gospel/R&B.
  If it does, dial those down and push `distorted guitars / punk drums` up.

---

## How each track file is structured

Every `*-worship-punk.md` contains, top to bottom:
1. One-line description of the track's identity.
2. **Creative Direction** — topic, why it works, **Bible verses** (with where each lands in the lyric), emotional arc.
3. **Style / Tempo / Vocal** — prose detail.
4. **Full Lyrics** — readable draft with performance notes.
5. **Alternate Chorus Hook Options** — 6 each.
6. **⬇️ Ready to Drop Into Suno** — paste-exactly **Title / Style of Music / Exclude Styles / Lyrics** blocks. *(This is the part you copy into Suno.)*

---

## Status

**Done (12/12 tracks written + Suno-ready):** all rows in the index above.

**Open / next steps:**
- [ ] **Album title** — top candidates: **"Lovers of the Light"**, **"Already Won"**, **"Truth Has a Name"**, **"Hold the Line"**.
- [ ] **One-page album overview / liner doc** (could expand this file): final running order + a single unifying band-style descriptor so all 12 share one sonic identity, + album art prompt.
- [ ] **Generate & A/B in Suno**, then note which style-box tweaks each track needs after first listen.
- [ ] Watch the two flagged tracks on generation: **Kept the Faith** (don't let it drift country — fixed in the box, verify on render) and **Off the Fence** (don't let it drift gospel/R&B).
- [ ] Optional: a unifying motif — the word **"Light"** recurs; "Already Won" already reprises hooks from Anchor / Under / Lovers / Ever Learning to bookend the record.

**Unifying band-style seed** (drop-in base for any track, then customize):
> `melodic Christian pop-punk, distorted guitars, punk drums, passionate male lead, gang vocals, [BPM], key of [X], [mood]`

---

## Quick continue-on-PC checklist
1. `git pull` on branch `claude/canadian-campfire-song-87x8lh`.
2. Open the track's `.md` → scroll to **⬇️ Ready to Drop Into Suno** → copy Title / Style / Exclude / Lyrics into Suno Custom Mode.
3. Edits to lyrics/style: change both the readable section *and* the paste-exactly Suno block so the file stays the source of truth.
4. Keep every Style box **≤200 chars** and Lyrics **≤3,000**.
