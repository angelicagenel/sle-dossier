# Internal production files — do not link publicly

Everything in this folder is production/editorial control documentation for
Spanish Learning Edge (SLE) staff and contractors (Claude, Marcos, and future
production help). None of it is written for prospective institutional
clients, instructors, or students.

- `00_FINAL_PRODUCTION_AUTHORITY.md` — the single source of truth for SP101
  curriculum decisions: canonical narrative route, cast, Cuéntame narratives,
  the full 24-lesson linguistic inventory, non-negotiable limits, vocabulary
  (P/M/R) rules, and the audience-separation rules that govern what may
  appear on public pages vs. instructor-facing pages vs. here.
- `SP101_CT2_AUDITORIA_LINGUISTICA_Y_CULTURAL.md` — the CT2 (Los alebrijes de
  Pedro Linares) language and culture audit referenced by the production
  authority doc.

## Why this folder exists

The August 10, 2026 production audit found this content linked directly from
public dossier pages (`sle-linguistic-competence-map.html`), which mixed
internal editorial control language (exact productive ceilings, receptive-only
controls, source-attribution audits) into material meant for prospective
clients. That link has been removed from every public/instructor page.

## This is not enough on its own

Moving these files into `internal/` and removing public links stops normal
site navigation from reaching them, but **the repository itself is still
public** (or may be) and GitHub Pages serves from the repo root — anything
in this folder is still reachable by a direct URL to anyone who has it.
Hiding the link does not make the content private.

Before this project is client-facing, someone with repo-admin access should:

1. Move `internal/` (and this README) to a **private** production repository
   that only SLE staff and contractors can read, and
2. Confirm the public/GitHub Pages repository no longer contains this folder
   at all.

Until that migration happens, treat every file here as "linked nowhere, but
not actually secret."
