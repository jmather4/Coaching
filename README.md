# Coaching

CoachLog — single-file coaching app (`index.html`) for AFC Urmston Meadowside, published with GitHub Pages at https://jmather4.github.io/Coaching/.

No build step. Team data lives in a Google Sheet, not in this repo.

## Full-Time auto-update

The League tab can read the league table and results straight from FA Full-Time. Full-Time has no public API and blocks server traffic, so this uses the code snippets a Full-Time admin generates: paste them under League → Full-Time auto-update. The snippet loads on the coach's own device in a sandboxed hidden frame, and its table goes through the same code as a manual paste. If Full-Time returns nothing or something unreadable, the existing table is left alone. Cup rounds are still pasted by hand.
