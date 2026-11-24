# MDOE407 — simulation prototypes

Course: **Managing Underperformance: Effective Performance Conversations for New Managers**.
Fictional company (Lumera Aesthetics), fictional people, invented data.

Four levels, each giving less support than the one before it.

| Level | Path | What it is |
|---|---|---|
| — | `/` | Landing page linking all four |
| 1 | `/nadia/` | **Guided walkthrough.** Linear PREPARE run with Nadia Cole; model answers and self-check. |
| 2 | `/hub/` | **Lumera Learning Hub.** Walk-around office, five formative activities (A1–A5). |
| 3 | [edu.delightex.com/CRY-QSY](https://edu.delightex.com/CRY-QSY) | **Weigh the explanation.** VR room in CoSpaces; hosted there, not here. |
| 4 | `/jordan/` | **The conversation with Jordan.** Free-text summative task, running on the rule-based stand-in. |

## Status
- The **live AI service** behind level 4 is specified and coded, but **proposed, not deployed**.
  What is published here is the rule-based stand-in, which exercises the same interface and logic.
- The **facilitator record pipeline** is likewise a design, not a running service.
- Scoring bands, a reliability check on the AI's labels, and a pilot with real learners all come next.

## Notes
- Static sites: no build step, no server.
- Learner progress is stored in the browser only (`localStorage`), per device.
- Fonts load from Google Fonts; everything falls back to system fonts offline.
- This repository is public, so page source is readable — including the hidden causes in level 4.
  Fine for a prototype demonstration; it would need rethinking before real assessment use.
