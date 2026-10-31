> **AI Assistance Declaration:** I used ChatGPT (GPT-6, October 30–31, 2026) for README structure, wording, R Markdown documentation suggestions, and review. Prompts used: see `AI_Prompts_Appendix.md`. Verification methods: **[complete with checks you actually performed]**. All final calculations are done by myself. I am responsible for the accuracy and originality of this work.

# Synthetic Student Marks Analysis

An educational R Markdown project that documents a small analysis of **synthetic student marks**. It demonstrates reproducible documentation, basic data validation, descriptive statistics, and a bar chart without using personal data.

## Project Overview

The project answers a simple question: how can a small set of fictional assessment scores be summarized and visualized clearly? It is designed for **BDA400 Assignment 1 — Markdown Buddy**, with an emphasis on documentation quality and responsible AI assistance rather than substantive educational conclusions.

## Repository Contents

| File | Description |
| --- | --- |
| `README.md` | Project overview, setup, usage, and AI disclosure |
| `StudentMarksAnalysis.Rmd` | Documented R workflow, calculations, and visualization |
| `Reflection.md` | Provisional reflection drafts; replace questions with the LMS wording |
| `AI_Prompts_Appendix.md` | Prompt record and verification/refinement log |

## Requirements

- R (base R is sufficient for the analysis)
- RStudio or Posit Cloud for editing and knitting (recommended)
- R package `rmarkdown` and a compatible Pandoc installation for HTML rendering (RStudio typically bundles Pandoc)

## Installation

1. Download the repository ZIP from GitHub and extract it, or clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/markdown-buddy-sunilkumar.git
   cd markdown-buddy-sunilkumar
   ```

   Replace `YOUR-USERNAME` with your own GitHub username after creating the repository.
2. Open `StudentMarksAnalysis.Rmd` in RStudio.
3. If `rmarkdown` is not installed, run:

   ```r
   install.packages("rmarkdown")
   ```

4. Select **Knit** to render the report as HTML, or run:

   ```r
   rmarkdown::render("StudentMarksAnalysis.Rmd")
   ```

## Inputs and Analysis

The `.Rmd` defines six fictional student IDs and scores directly in a code chunk. It validates that scores are numeric, present, and within 0–100, then calculates the mean, median, minimum, and maximum and draws a bar chart. No CSV download or real dataset is needed.

## Example Code

This is an illustration of the base R syntax used in the report:

```r
scores <- c(72, 85, 91, 68, 77, 89)
mean(scores)
median(scores)
```

**Run and independently verify these calculations yourself.** Do not copy unverified results into the assignment.

## Expected Outputs

- A printed table of six fictional IDs and scores
- A summary table of four descriptive statistics
- A bar chart showing scores by fictional ID
- An HTML report after a successful knit

## Documentation Review and Verification

Use the following checklist and record actual observations in `AI_Prompts_Appendix.md` and the `.Rmd` verification log.

- [ ] Compare the section organization with a real tidyverse GitHub README and record two observations.
- [ ] Preview `README.md` in GitHub and check headings, lists, table, links, and code fences.
- [ ] Knit `StudentMarksAnalysis.Rmd` in RStudio/Posit Cloud and inspect the chart and tables.
- [ ] Recreate the primary calculations in Google Sheets.
- [ ] Independently cross-check the results without relying on AI calculations.
- [ ] Perform a self- or peer-spot-check and document two specific refinements.
- [ ] Replace the provisional reflection questions with the three exact LMS questions.

## Limitations

The sample is intentionally small and synthetic; it cannot support conclusions about actual students. The repository demonstrates documentation practices rather than a production analysis.

## License

No open-source license has been granted. This repository is provided as coursework; permission to reuse is not automatically granted.

## AI Assistance Disclosure

- **Tool:** ChatGPT (GPT-6), October 30–31, 2026.
- **Main requests:** README structure and Markdown formatting; project README drafting; R Markdown documentation; rubric-based review and refinement. See `AI_Prompts_Appendix.md` for the prompt record.
- **AI-assisted revisions in this draft:** Clarified setup steps, explained expected outputs, improved heading consistency, and added a verification checklist.
- **Student edits and verification:** **[Replace with changes you personally made and previews/calculations you actually completed.]**
