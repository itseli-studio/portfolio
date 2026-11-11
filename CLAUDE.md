# Portfolio website — project context

This repository holds the company portfolio website for itseli studio (owner: Eli Weissman).
Work happens across multiple Claude Code cloud sessions and devices, so this repo is the
single source of truth. Anything not committed and pushed is lost when a session ends.

## Status
- Phase: **design exploration**. Direction as of 2026-11-11: a product/app-style website (see the
  "Notes for Claude" tab in Eli's Studio Website Brief doc). Explorations are listed in
  `docs/brief.md`. Nothing has been built yet.
- Do not start building the site until the owner says so.

## Skills to use (Eli's instruction, 2026-11-10)
For all work on this project, use these skills:
- **Superpowers**: start with `superpowers:brainstorming` before any creative or build work, then
  `superpowers:writing-plans` and the rest of the Superpowers workflow (TDD, verification before
  claiming done, code review).
- **frontend-design** (`frontend-design:frontend-design`) for visual direction and UI building.
- **ui-ux-pro-max** (`anthropic-skills:ui-ux-pro-max`) for UX, accessibility, layout, type and color checks.

Design specs from brainstorming go in `docs/superpowers/specs/`, plans in `docs/superpowers/plans/`.

## Where things live
- `docs/brief.md` — the project brief: company info, services, projects, brand, content, and
  decisions. Update it whenever new details or decisions come up, and commit it.

## Working rules
- Take no design inspiration from Eli's other Claude projects (itseli OS, its client portal,
  itseli finances, Tribal website prototype). Exception, per Eli's doc (2026-11-10): take layout,
  button shapes, pill buttons, rounded corners, card sizes and spacing from Eli's **Mouse** Figma
  files (landing page and app; links are in the doc's Notes tab). Never Mouse's colors.
- The doc has a **"Notes for Claude" tab**. Read it every session along with the main tab.
- **Source of truth for strategy, voice, structure and copy: Eli's Google Doc titled "Studio
  Website Brief"** (find it by searching Eli's Google Drive for that title; the link is kept out of
  this public repo on purpose). Eli keeps editing it. Re-read it at the start of every session and
  before writing a spec, a plan or any site copy. Where it and `docs/brief.md` disagree, the doc
  wins. Older Drive docs about Brand Foundation and the old offer are out of date.
- This repo is public. Don't commit private links, client documents or internal notes.
- Never use em dashes in site copy (the studio brief asks for commas, periods or a simple hyphen).
- Commit and push after every meaningful change so the next session picks it up.
- Record decisions in `docs/brief.md` (under "Decisions") rather than only in chat.
- Connected tools that may hold source material: Figma, Google Drive, ClickUp.
