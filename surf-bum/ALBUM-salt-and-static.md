# SALT & STATIC — a surf-bum lo-fi album

*A full 10-track album, one day at a beach town, dawn to dark. Lo-fi throughout — cassette hiss, vinyl
crackle, warped tape, garbled AM radio — but the texture changes track to track so it never feels like one
flat filter: bedroom-4-track hush, boombox-radio garble, warm nostalgic cassette, community vinyl warmth,
grainy home-movie warp. Three tracks open on found audio — a marine-conditions radio report and two street
interviews — mixed in like they were taped off the actual day. Clean lyrics throughout, mostly light and
vibes-first, with a couple of character-driven detours. Cloudlight Proxy.*

> **Brief:** a full album, kept lo-fi but varied, with a few tracks opening on low-quality beach-condition
> news reports or interviews with a surfer/shop customer — then run the whole thing through a surfer critic board.

---

## The Running Order — one day, dawn to dark

| # | Track | File | What it is |
|---|---|---|---|
| 1 | **Before the Sun** | `before-the-sun-lofi-surf.md` | Pre-dawn drive to the beach, hushed and sparse. Ends on the actual sunrise. |
| 2 | **Salt Air** | `salt-air-retro-surf.md` | Morning paddle-out. Half-time floating breakdown mid-song. |
| 3 | **Small Craft Advisory** | `small-craft-advisory-lofi-surf.md` | 📻 *Opens on a garbled AM marine-conditions report.* Chasing the surf report, upbeat and a little goofy. |
| 4 | **Board Break** | `board-break-instrumental-surf.md` | Fast, almost-wordless instrumental. Wipes out mid-track, recovers. |
| 5 | **Open Til the Swell Comes In** | `open-til-the-swell-comes-in-surf-shop.md` | Life behind the counter at the shop. Ends mid-word as the door slams. |
| 6 | **Forty Summers** | `forty-summers-lofi-surf.md` | 🎙️ *Opens on an interview with a local surfer, 40 years in.* Warm tribute to the guy who never left. |
| 7 | **Home Movie** | `home-movie-lofi-tape-surf.md` | Grainy Super-8-style recap of the day, tape warps and "rewinds" mid-song. |
| 8 | **Not on Any Map** | `not-on-any-map-lofi-surf.md` | 🎙️ *Opens on an interview with a shop customer.* Communal anthem for the hidden-gem town itself. |
| 9 | **Tiki Torch Nights** | `tiki-torch-nights-exotica-surf.md` | Evening lounge wind-down — vibraphone and marimba take over from guitar. |
| 10 | **Night Swim** | `night-swim-dreamy-surf.md` | The close. Deliberately hushed, no big final chorus — just quiet water and stars. |

**The found-audio tracks (3):** Small Craft Advisory (news report), Forty Summers (surfer interview), Not
on Any Map (customer interview) — spaced out through the middle of the album so they land like real
"local color," not a repeated gimmick.

---

## Bonus Disc — the Lo-Fi Tape Edition
A parallel "found on a warped cassette" pressing of five tracks from the main album, same words and
structure, pushed further into full tape degradation:
`salt-air-lofi-tape-version.md` · `board-break-lofi-tape-version.md` ·
`tiki-torch-nights-lofi-tape-version.md` · `night-swim-lofi-tape-version.md` ·
`open-til-the-swell-comes-in-lofi-tape-version.md`
*(Home Movie is already the tape-aesthetic original, so it doesn't get a separate bonus cut.)*

---

## The Surfer Critic Board
*Criteria: **Hook · Replay · Lo-Fi Authenticity · Surf Culture Accuracy · Cohesion** (10 each, 50/judge, 250).*
A different panel than the usual pop-critic board — this one's all surf-world.

- **"Wax" Wilson** — old-school shop owner, been running the same board rack for 30 years
- **Kai Nakamura** — touring pro surfer, judges on energy and whether it'd actually get played at a beach party
- **Sandy Reyes** — surf-mag editor / zine writer, judges the storytelling and hooks
- **"Salty" Sam** — pirate-radio-style beach DJ, judges production and whether the lo-fi feels earned or gimmicky
- **Lulu Chen** — Gen-Z grom, TikTok surf creator, judges replay and shareability

| Judge | Hook | Replay | Lo-Fi | Culture | Cohesion | Total | Note |
|---|---|---|---|---|---|---|---|
| **"Wax" Wilson** | 8 | 9 | 9 | 10 | 9 | **45** | "Small Craft Advisory and Open Til the Swell Comes In — those are word-for-word how it actually is. Forty Summers might be about three guys I know personally." |
| **Kai Nakamura** | 9 | 9 | 8 | 9 | 9 | **44** | "Board Break's wipeout section is the realest 'oh no' moment on the record. This would absolutely get played driving to a dawn session." |
| **Sandy Reyes** | 9 | 8 | 9 | 9 | 9 | **44** | "The interview intros are the smartest move here — they earn the nostalgia instead of just claiming it. Not on Any Map is a genuine town anthem." |
| **"Salty" Sam** | 8 | 9 | 10 | 9 | 9 | **45** | "The lo-fi never sounds like one preset slapped on ten songs — bedroom hush, boombox garble, warm cassette, they're all doing different jobs. That's the hard part, and it's right." |
| **Lulu Chen** | 9 | 9 | 8 | 8 | 9 | **43** | "Night Swim closing it out this quiet is such a good choice — most albums would end loud. I'd replay the whole thing front to back, not just skip to favorites." |

**Total: 221/250 — a lo-fi surf album that actually earns the word "album."** Verdict: *"It's not ten
disconnected vibes tracks — it's one day, and you can feel the light change from track to track. The found
audio is the glue: it makes the whole thing sound like something that actually happened, not something that
was written to sound like it did."*

---

## Notes for building this in Suno
- Each track file has its own complete **Title / Style of Music / Exclude Styles / Lyrics** paste block —
  generate them one at a time in Suno's Custom Mode, same as every other song in this catalog.
- For the three found-audio tracks, if Suno smooths out the "garbled radio" or "interview" intro too much,
  push harder on the tag inside `[News Report — Intro]` / `[Interview — Intro]` — e.g. add `heavily degraded
  broadcast, distant mic, wind noise` directly to that section's parenthetical.
- Track order matters for the "day unfolding" feel — if generating a listening sequence (not uploading to a
  DSP with metadata), keep them in the 1–10 order above.
- The Bonus Disc lo-fi versions can either replace their main-album counterparts entirely, or sit alongside
  them as a "Side B" — both work; it's a style choice, not a technical requirement.
