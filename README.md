# Wayne AI Tell Scanner

A personal-use, rule-based AI-sheen scanner built in Wayne-mode for draft triage, not false-certainty authorship detection.

## What it does

- Flags corporate filler, soft transitions, abstraction fog, hedging, repetition, flat cadence, and passive drift.
- Scores likely AI-sheen risk from 0 to 100.
- Generates Wayne-mode rewrite prompts.
- Exports a plain-text audit report.
- Runs fully client-side as a static app.

## Files

- `wayne-ai-tell-scanner.html` — the app
- `phrases.json` — editable phrase and pattern library
- `README.md` — this file
- `LICENSE` — MIT license
- `.gitignore` — basic repo hygiene

## Local use

1. Download or clone the repo.
2. Open `wayne-ai-tell-scanner.html` in your browser.
3. Paste text and run a scan.

## GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder.
3. In GitHub, open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the main branch and root folder.
6. Save, then wait for the site URL to appear.

## Editing the scanner

The phrase library lives in `phrases.json`. You can add or remove trigger phrases there without rewriting the full app.

## Positioning

This tool is strongest when treated as a style-audit assistant. It detects suspicious writing patterns, not authorship proof.
