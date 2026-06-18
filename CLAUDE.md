# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repo Is

A student lab submission for VinUni's AI Product Strategy track (Day 16). There is no build system, no tests, no package manager. The repo contains markdown worksheets and an HTML slide deck.

## Structure

- `worksheet/01-case-analysis.md` — Lab 1 (completed): Chegg case analysis with evidence, four judgments, peer discussion notes, and final verdict.
- `worksheet/02-jtbd-project-analysis.md` — Lab 2 (blank): apply Jobs-to-be-Done framework to the student's team project.
- `presentation.html` — Self-contained HTML/CSS/JS slide deck (11 slides) presenting the Lab 1 Chegg analysis. Arrow keys or buttons navigate. No external dependencies beyond a Google Fonts import.
- `README.md` — Submission metadata and navigation (in Vietnamese).
- Companion reference (not in repo): `Strategyn_JTBD_Playbook.pdf`.

## Key Constraints When Editing

- All content is in Vietnamese. Keep responses and edits in Vietnamese unless the student asks otherwise.
- Worksheets are simultaneously guides, worksheets, and submission files — preserve all section headers, tables, and checklist structure. Do not remove or reorder sections.
- Lab 1 rule: every judgment must cite at least one evidence entry (E1–E5). No evidence = no claim.
- Lab 2 rule: core JTBD statements must be solution-free (no product names, no "AI", no "chatbot", no "app"). Format: `verb + object + contextual clarifier`.
- Job stories follow: `When [trigger], I want to [motivation], so I can [outcome]`.
- JTBD lite map uses 8 steps: define → locate → prepare → confirm → execute → monitor → modify → conclude.
- AI should help find sources, gather data, and draft prose — but the student must verify sources, check figures, and write their own verdicts and "permanent change" statements.

## Presentation Constraints

- `presentation.html` is a single-file slide deck — all CSS and JS are inline. No build step.
- Uses CSS custom properties (`:root` vars) for theming. Keep the existing design system (`--bg`, `--accent`, `--accent2`, etc.) when adding or editing slides.
- Slide count is tracked dynamically via `querySelectorAll('.slide')`. Adding/removing a slide requires no JS changes.
