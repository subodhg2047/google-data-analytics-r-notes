# Google Data Analytics Certification — R Practice Notebook

A consolidated set of R practice notes built while completing the **Google Data
Analytics Professional Certificate**. Covers base R, the `tidyverse`, data cleaning,
grouping/summarizing, bias checking, and progressive `ggplot2` visualization —
structured as a single reference notebook for revision.

## 📘 Contents

| Section | Topics |
|---|---|
| 1. Environment Setup | Package installation & loading |
| 2. Dates & Times | `lubridate` basics (`today()`, `mdy()`, `ymd_hms()`, etc.) |
| 3. Base R Fundamentals | Arithmetic, `if`/`else` logic, `subset()` with logical operators |
| 4. Importing & Inspecting Data | `head()`, `str()`, `glimpse()`, `summary()` on `penguins`, `diamonds`, `mtcars` |
| 5. Data Cleaning & Wrangling | `rename()`, `summarise()`, `clean_names()`, `mutate()`, `select()`, `separate()`, `unite()` |
| 6. Grouping & Summarizing | `group_by()`, `filter()`, piping with `%>%` |
| 7. Checking for Data Bias | `SimDesign::bias()` on actual vs. predicted values |
| 8. Data Visualization | Full `ggplot2` progression: scatter plots → color/shape/size mapping → trend lines → faceting → boxplots/violins/density → bar charts → annotations → Anscombe's Quartet & Datasaurus Dozen (why visualization matters) |

## 🛠 Tools & Packages

`tidyverse` · `palmerpenguins` · `skimr` · `janitor` · `here` · `Tmisc` · `datasauRus` · `SimDesign`

## 📂 Files

- `Google_Data_Analytics_Notebook.Rmd` — source R Markdown file
- `Google_Data_Analytics_Notebook.md` — GitHub-rendered version with inline plots
- `Google_Data_Analytics_Notebook.html` — full knitted HTML report ([view live](#) via htmlpreview.github.io or GitHub Pages)
- `Google_Data_Analytics_Notebook_files/` — generated plot images used by the `.md` render

## 🚀 Running it yourself

```r
# Clone the repo, then in R/RStudio:
install.packages(c("tidyverse", "palmerpenguins", "here", "skimr",
                    "janitor", "Tmisc", "datasauRus", "SimDesign"))
rmarkdown::render("Google_Data_Analytics_Notebook.Rmd")
```

## 📊 Datasets Used

All datasets are built into R packages — no external downloads required:
`palmerpenguins::penguins`, `ggplot2::diamonds`, `datasets::airquality`,
`datasets::mtcars`, `datasets::ToothGrowth`, `Tmisc::quartet`, `datasauRus::datasaurus_dozen`.

## 👤 Author

**Subodh** — Master of Applied Business (Business Analytics), Unitec Institute of Technology.

---

*Notes compiled for personal revision during the Google Data Analytics Certification.*
