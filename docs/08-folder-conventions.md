# Folder and Naming Conventions

CUE units should be easy to inspect, revise, and reuse.

## Recommended top-level folder

```text
units/
  Unit_Name/
    00_unit_brief.md
    01_source_discovery.md
    02_reading_sequence.md
    03_handouts/
    04_argument_maps/
    05_paper_prompts/
    06_10th_grade/
    07_12th_grade/
    notes_after_teaching.md
```

This repo does not yet contain a real unit. When the first test unit is built, place it under `units/`.

## Naming rules

Use lowercase kebab-case for file names when possible:

- free-will.md
- hobbes-liberty-and-necessity.md
- aristotle-voluntary-action.md

Use numbered prefixes when order matters:

- 00_unit_brief.md
- 01_source_discovery.md
- 02_reading_sequence.md

## Source files

If storing source excerpts separately, use:

```text
sources/
  author-work-section.md
```

Example:

```text
sources/
  hobbes-leviathan-ch21.md
```

## Handout files

Use:

```text
handouts/
  01_author-short-title.md
  01_author-short-title.tex
  01_author-short-title.pdf
```

Only create `.tex` and `.pdf` when moving from draft to formatted classroom handout.

## After-teaching notes

Every taught unit should eventually have `notes_after_teaching.md`. This is where the living curriculum improves.
