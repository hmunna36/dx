# DX Level 1 — Study App

A single self-contained `.html` file for cramming the **2024 HE Domain DX Level 1** certification exam. Pass mark 80/100.

Seven tabs: Past → Drill → Blanks → Study → Cards → Cheat → Check.

- **33 past-paper MCQs and 12 subjectives** drawn from four papers, each badged with how many of the four it appeared in
- **117 drill MCQs** across the six modules, with live scoring against the 80% pass line
- **52 fill-in-the-blank items**, graded on normalized input with per-item hints
- Searchable study notes, **~78 flashcards across 6 decks**, a print-friendly cheat sheet, and a claims-audit tab for facts in the compiled notes that don't trace back to the source deck
- Every question carries a **tier (1–5)** and an **estimated appearance probability** derived from four papers: three recalled sittings (24/03/26, 11/05/26, 25/05/26) and the official Confluence sample (18/09/26). The official sample is the examiner's own practice material — where a recollection disagrees with it, trust the sample.
- No build step, no dependencies, no `localStorage`/`sessionStorage` — works offline and inside the Claude.ai Artifact viewer. Progress is in-memory and resets on refresh.

## Use it

Open `DX_Level1_Study_App.html` directly in a browser — no server needed.

## Deploy

This repo includes a `vercel.json` rewrite so a zero-config static deploy serves the app at the root URL:

1. Import this repo at [vercel.com/new](https://vercel.com/new)
2. Framework preset: **Other** (static HTML, no build step)
3. Deploy
