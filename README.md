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

- **16 Leadership Principles** question bank (at least one behavioral question each)
- **5 random questions** per mock interview
- **STAR heuristic grading** (Situation/Task 25%, Action 40%, Result 35%)
- **Scorecard dashboard** with per-question feedback and missing-structure alerts
- **Dark / light theme** toggle (enterprise slate + corporate blue)

## Stack

Vanilla HTML, CSS, and JavaScript in one `index.html` file. No frameworks.
