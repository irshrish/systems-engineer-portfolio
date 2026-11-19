# Systems Engineer Portfolio — Mohamed Ersath

A single-page portfolio site: one self-contained HTML file, no build step, no framework.

**Live view:** https://irshrish.github.io/systems-engineer-portfolio/

## What's in here

| file | what it is |
|---|---|
| `index.html` | the site. Styles, content and the one screenshot are all inline, so it opens straight from disk. |
| `Mohamed-Ersath-Portfolio.html` | the same page under a name-friendly filename, for sharing or printing. |

Open either file in a browser — no server needed.

## Contents

About, career timeline, project cards (parking kiosk suite, Windows cutting-planner apps, Android apps, a PC assistant), capability list, and contact link. The dashboard image on the Projects card is a **demo view built on sample data** — it is not connected to any live system, and the numbers in it are illustrative.

## Tech

Hand-written HTML + CSS with a small amount of vanilla JavaScript for the scroll reveals and theme toggle. Design tokens are kept in one block at the top of the file, so the whole colour scheme can be restyled in one place.

## Deploying

GitHub Pages serves `index.html` from the repository root on the `main` branch. Any static host works the same way — the file has no external dependencies.
