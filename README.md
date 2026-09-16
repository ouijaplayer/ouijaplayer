# Amazon STAR Mock Interviewer

A single-file, highly responsive web app for practicing Amazon Leadership Principles behavioral interviews using the STAR framework.

## Run it

Open `index.html` in any modern browser — no build step or server required.

```bash
open index.html   # macOS
xdg-open index.html   # Linux
```

Or serve locally:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Features

- **Coaching + practice question bank** — Leadership Principle prompts from the STAR coaching guide, behavioral drills from the practice packet, and coverage of all 16 LPs
- **5 random questions** per mock interview
- **Coaching-aligned STAR grading** (Situation/Task 25%, Action 40%, Result 35%) — flags vague actions, blended S/T, “we” language, and missing numbers
- **Scorecard dashboard** with per-question feedback
- **Dark / light theme** toggle (enterprise slate + corporate blue)

## Stack

Vanilla HTML, CSS, and JavaScript in one `index.html` file. No frameworks.
