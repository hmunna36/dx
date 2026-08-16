# DX Level 1 — Study App

A single self-contained `.html` file for cramming the **2024 HE Domain DX Level 1** certification exam.

- 102 drill questions across 6 modules, with live scoring against the 80% pass line
- Searchable study notes, six flashcard decks, a print-friendly cheat sheet, and a claims-audit tab for facts in the compiled notes that don't trace back to the source deck
- No build step, no dependencies, no `localStorage`/`sessionStorage` — works offline and inside the Claude.ai Artifact viewer

## Use it

Open `DX_Level1_Study_App.html` directly in a browser — no server needed.

## Deploy

This repo includes a `vercel.json` rewrite so a zero-config static deploy serves the app at the root URL:

1. Import this repo at [vercel.com/new](https://vercel.com/new)
2. Framework preset: **Other** (static HTML, no build step)
3. Deploy
