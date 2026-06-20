# Fluidez — Luzerndütsch (Lucerne Swiss German)

Content repo for the Fluidez app. Code: **gsw-lu** · Flag: 🇨🇭

## What's inside (`content/`)
- **81 lessons** — Phases 0→7, a continuous personal journey: arriving in Lucerne
  knowing nothing (s00 "Grüezi") → being taken for a local (finale s710, which
  mirrors s00). 14 sentences each, 10 warm-up words each.
- **40 scenarios** — 5 per phase, branching good/ok/bad replies with feedback.
- **dictionary/core.json** — 625 words; covers every warm-up word in the course.
- **patterns/core.json** — 7 grammar patterns (the -li diminutive, particles
  gäll/halt/eba, past tense with ha/bi, Swiss vocab, sound shifts, telling time,
  Grüezi vs Sali).
- **manifest.json** — indexes everything.

## Phase arc
0 Aachoo · 1 Sich z'rächtfinde · 2 Lüt kenneläre · 3 Sich behaupte ·
4 Change nöch · 5 Yneläbe · 6 Tüüff Lozärnerisch · 7 Eine vo öis

## Authenticity note
Pure dialect, texting-style but one consistent spelling per word so the tap
dictionary works. Where an authentic Luzerndütsch form wasn't certain, the
content falls back to Standard German rather than inventing dialect. Native
speakers are the final authenticity check.

## To publish
1. Create a GitHub repo named **fluidez-gsw-lu** under user **scenicprints**.
2. Upload the **contents of this folder** (so `content/manifest.json` is at
   `https://raw.githubusercontent.com/scenicprints/fluidez-gsw-lu/main/content/manifest.json`).
3. In the **fluidez-languages** repo, ensure `languages.json` includes the
   gsw-lu entry (already drafted). No app rebuild needed — the app reads the
   registry and fetches this repo automatically.
