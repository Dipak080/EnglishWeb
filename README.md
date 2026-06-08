# English Vocabulary — 10 Levels

A simple, mobile-friendly website to learn 3000 English words, organised into 10 levels (easy → hard, 300 words per level).

## Features
- 10 level tabs with per-level progress counts
- Each word shows: number, word, type and meaning
- Tap the checkbox to mark a word learned — saved in your browser via **localStorage** (progress is per-device)
- Progress bar and percentage per level
- Search by word or meaning
- "Hide done" to focus on words you haven't learned yet
- "Reset level" to clear ticks for a level

## Files
- `index.html` — the entire app (HTML + CSS + JavaScript)
- `vocab.json` — all 3000 words
- `English_Vocabulary_10_Levels.xlsx` — original source spreadsheet

## Run locally
Because the page loads `vocab.json`, open it through a local server (not by double-clicking):

```bash
python -m http.server 8765
```

Then visit http://127.0.0.1:8765

## Deploy
Static site — works on Vercel / Netlify / GitHub Pages with no build step.
