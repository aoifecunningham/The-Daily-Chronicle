# The Daily Chronicle — AI Detection Desk

Static browser experiment. Keep `index.html`, `styles.css`, `script.js`, and the `assets/` folder together. Open `index.html` in a modern browser.

## Features
- Four scenario-based pre-game questions and four different post-game questions.
- Newspaper fact-checker role and goal: earn six verification stamps.
- Three strategy blocks: visual inspection, source verification, context verification. Their order is shuffled each session.
- Six image cases: three local AI-generated image assets and three genuine Unsplash photographs (internet connection required for the genuine photos).
- Learning guide, 30-second timed number-order distractor, and three scored recall questions.
- Session summary CSV with one row; trial-level CSV with one row per answered question and right/wrong scoring.

No server, database, React, Node, or build step is used. AI images are generated examples; real images are genuine Unsplash photographs. A real photograph can still be misleading if its caption, date, or context is false.
