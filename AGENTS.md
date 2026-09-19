# r4ds2e Project Memory

## Project Purpose

A chapter-by-chapter workthrough of *R for Data Science (2nd Edition)* by Hadley Wickham (https://r4ds.hadley.nz/). The goal is twofold:
1. A **personal guidebook** for Drew — clear notes and annotated code covering R concepts introduced in the book.
2. **Reference material** for the organization (First Tee West Michigan).

## Repository

- **Local working directory:** `c:/Users/Drew/Documents/R/r4ds2e-1`
- **Personal fork (origin):** https://github.com/drewjones89/r4ds2e
- **Organization repo (upstream):** https://github.com/FirstTee-WestMichigan/r4ds2e

### Git workflow
Work in the local `r4ds2e-1` folder. To contribute to the org repo:
- Stage → Commit → `...` menu → **Push to... → upstream**
- Do NOT use "Sync Changes" (pushes to fork, not org repo)

## File Naming Convention

One `.qmd` file per chapter, named: `chapter_N_topic.qmd`

**Example:** `chapter_1_data_visualization.qmd`

## Chapter Files

| Chapter | File | Status |
|---------|------|--------|
| 1 | `chapter_1_data_visualization.qmd` | In progress |

## Conventions for Notes and Code

- Use Quarto (`.qmd`) format, rendered as HTML
- Each chapter file should load required packages in the first code cell
- Annotate code with comments explaining the *why*, not just the *what*
- Common packages: `tidyverse`, `palmerpenguins` (Ch. 1+)
