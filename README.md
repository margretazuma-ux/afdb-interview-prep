# AfDB Interview Prep — Knowledge Quiz

A single-file, interactive quiz app for preparing to discuss the African Development Bank's strategic direction — its mission, priorities, and the challenges it names for itself.

**Live site:** [https://margretazuma-ux.github.io/afdb-ypp-interview-prep/](https://margretazuma-ux.github.io/afdb-ypp-interview-prep/)

## What it does

The app draws random questions from two source documents:

- **The Ten-Year Strategy 2024–2033** (AfDB) — organized around the Bank's "High 5s" pillars, cross-cutting priorities, global public goods, private-sector finance strategy, and the risks/challenges the Bank names for itself.
- **Dr. Sidi Ould Tah's presidency vision document** — organized around his "Four Cardinal Points," plus his proposals for reforming the Bank internally.

You can pick specific themes to drill on, mix everything for random practice, or focus on the "Synthesis" questions that ask you to compare and connect ideas across both documents.

Each question has a "Reveal model answer" option showing key points to hit, a model answer, and a direct quote from the source document (with page citation) so you can check your own phrasing against the real language.

## How to use it

1. Open the page (via the GitHub Pages link above, or by opening `index.html` directly in a browser).
2. Check the theme(s) you want to practice, or click "Mix everything."
3. Click "Start / update session."
4. Read the question, answer it out loud (use the notes box if you want to jot down key points first), then click "Reveal model answer" to compare.
5. Mark "Got it" or "Needs review" to move to the next question — your session stats reset each time you reload the page (nothing is saved or tracked beyond the browser tab).

## Updating the content

The whole app — including all questions, answers, and quotes — lives in a single `QUESTIONS` array inside `index.html`. To add, edit, or remove questions, open the file, find the `QUESTIONS` array, and edit the relevant entries directly. No build step or dependencies are needed; it's a self-contained HTML/CSS/JavaScript file.

## Source documents

- African Development Bank, *Ten-Year Strategy 2024–2033: Seizing Africa's opportunities for a prosperous, inclusive, resilient, and integrated continent* (2024).
- Dr. Sidi Ould Tah, *Building Africa's Prosperity: Smart Policy and Innovation* — vision statement for the AfDB presidency (May 2025).

Page citations in the app refer to each document's own internal pagination, not PDF page numbers.
