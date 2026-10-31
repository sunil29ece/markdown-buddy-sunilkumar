# Student Marks Analysis in R

> **AI Assistance Declaration:** I used ChatGPT (GPT-6, October 30, 2026) to draft documentation structure, explanatory text, and an example R Markdown workflow. Main prompts and key responses are recorded in [AI_Prompts_Appendix.md](AI_Prompts_Appendix.md). I will verify the Markdown in GitHub and run/knit the R Markdown file in RStudio or Posit Cloud before submission. All final calculations and interpretation must be checked by me. I am responsible for the accuracy and originality of the submitted work.

## Project Overview

This beginner-friendly project demonstrates how R can summarize and visualize **synthetic** student marks. It also demonstrates readable project documentation with GitHub-flavored Markdown and R Markdown.

## Objectives

- Create a small synthetic data frame of student marks.
- Calculate descriptive statistics using base R.
- Produce a bar chart of student marks.
- Explain inputs, outputs, and steps in a reproducible R Markdown document.

## Repository Contents

| File | Description |
| --- | --- |
| `README.md` | Project overview, setup, usage, and AI disclosure |
| `StudentMarksAnalysis.Rmd` | Documented R code and chart |
| `Reflection.md` | Draft reflections; replace question placeholders with exact LMS questions |
| `AI_Prompts_Appendix.md` | Main prompts and AI-generated response summaries |

## Requirements

- R (recent version)
- RStudio or Posit Cloud (recommended)
- `rmarkdown` and a working Pandoc installation for knitting to HTML (RStudio includes Pandoc)

The analysis uses **base R**, so no additional analysis packages are needed.

## Installation

1. Download or clone the repository.
2. Open `StudentMarksAnalysis.Rmd` in RStudio or Posit Cloud.
3. If needed, install R Markdown:

   ```r
   install.packages("rmarkdown")
   ```

4. Select **Knit** to render the document to HTML, or run the chunks individually.

## Example Usage

```r
marks <- c(78, 85, 92, 66, 88)
mean(marks)
```

The example demonstrates calculating the average of five synthetic marks. Verify the result by running the code in R.

## Data and Privacy

All student IDs and marks are invented for educational demonstration. The repository does not include personal student records or external datasets.

## Expected Outputs

- A table of five synthetic student marks
- Summary measures: mean, median, minimum, and maximum
- A bar chart showing the five marks

## Validation Checklist

- [ ] Preview `README.md` on GitHub and inspect headings, table, links, and code blocks.
- [ ] Run each R chunk and independently check the summary statistics.
- [ ] Knit `StudentMarksAnalysis.Rmd` to HTML and inspect the table and chart.
- [ ] Compare the README sections with an established R project's README.
- [ ] Record actual corrections made after reviewing the rendered files.
- [ ] Replace reflection question placeholders with the exact course questions.

## License

No license has been selected. This repository is intended as a course assignment; reuse rights are not granted by default.

## AI Assistance Disclosure

- **Tool:** OpenAI ChatGPT (GPT-6), October 30, 2026.
- **Main prompts:** “Provide GitHub repository code for BDA400 Markdown Buddy”; “Generate a professional README for a synthetic student marks analysis project”; “Document one R analysis in an `.Rmd` file with headers and code blocks”; “Provide reflection drafts and disclose AI assistance.”
- **Review and changes:** The draft was organized into focused sections and uses only synthetic data. Before submission, I will personally preview the Markdown, knit the R Markdown file, verify calculations, and document any further corrections. I will not claim those checks are complete until performed.
