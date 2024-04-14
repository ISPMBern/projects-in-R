# Projects in R

<img align="right" width="38%" src="phs-logo.jpg"> Information and course material for the [Projects in R](https://zuw.me/kurse/dt.php?kid=4701) course of the [Public Health Sciences Course Program](https://www.medizin.unibe.ch/studies/study_programs/phs_course_program) at the [University of Bern](https://www.unibe.ch)

- Course [GitHub repository](https://github.com/ISPMBern/projects-in-R)
- Course [GitHub Page](https://ispmbern.github.io/projects-in-R)

## Table of contents

1. [Preparation](#preparation)
2. [Timetable](#timetable)
3. [Slides](#slides)
4. [Exercises](#exercises)
5. [Data sets](#data-sets)
6. [Further online material](#further-online-material)
7. [Contact](#contact)

## Preparation

### Mandatory steps

Course participants will bring their own laptops with installed versions of [R](https://www.r-project.org), [RStudio](https://posit.co/products/open-source/rstudio), and [Git](https://git-scm.com):

1. [Download](https://cloud.r-project.org) and install R:
 - Windows: Click on "Download R for Windows", then click on "base", then click on the Download link.
 - macOS: Click on "Download R for macOS", then under "Latest release:" click on R-X.X.X-arm64.pkg or R-X.X.X-x86_64.pkg for Apple silicon (M1/M2) or older Intel Macs, respectively.
 - Linux: Click on "Download R for Linux" and choose your distribution for more information on installing R for your setup.
2. [Download](https://posit.co/download/rstudio-desktop) and install RStudio.
3. Install Git using the following [instructions](https://happygitwithr.com/install-git.html).
4. If you don’t already have one, don't forget to create a [GitHub](https://github.com) account.

**If you are new to R and RStudio, we recommend you to follow the 90-minute video tutorial [Introduction to R and RStudio](https://youtu.be/lL0s1coNtRk).**

### Optional steps

The following preparation steps are optional. You will also have time during the course to complete these steps.

1. Make sure RStudio knows about Git by following the corresponding section [here](https://sites.northwestern.edu/researchcomputing/using-git-and-github-with-r-rstudio/).
2. Install the `usethis` package for R using the following command: `install.packages("usethis")`
3. Set up Git using the following command:
`usethis::use_git_config(user.name = "Jane Doe", user.email = "jane@example.org")`
4. Generate a personal access token (PAT) and store your PAT as described in Section 9.3 and 9.4 [here](https://happygitwithr.com/https-pat.html#get-a-pat).

### Required packages

To work on the exercises, course participants have to install the following packages:

- `usethis` - Workflow package
- `gitcreds` - Queries Git credentials from R
- `here` - Easy file referencing
- `tidyverse` - A set of packages
- `medicaldata` - Medical data sets
- `cowplot` - Features to create publication-quality figures

Simply type `install.packages("packagename")`, but RStudio will ask you about it as well if you want to load a package that you haven't installed yet.

## Timetable

Day | Time | Topic | Slides | Lecturer(s)
--- | ---- | ----- | ------ | -----------
Monday, 22 April 2024 | 09:00-12:00 | Introduction to R, the tidyverse, and data wrangling | [HTML](https://ispmbern.github.io/projects-in-R/products/slides/2024_course_slides_01_wrangling.html) | Christian Althaus, Alan Haynes
Monday, 22 April 2024 | 13:00-17:00 | Data visualization with the tidyverse | [HTML](https://ispmbern.github.io/projects-in-R/products/slides/2024_course_slides_02_dataviz.html) | Christian Althaus, Judith Bouman, Martin Wohlfender
Tuesday, 23 April 2024 | 09:00-12:00 | Reproducibility and GitHub | [HTML](https://ispmbern.github.io/projects-in-R/products/slides/2024_course_slides_03_reproducibility.html) | Christian Althaus, Alan Haynes
Tuesday, 23 April 2024 | 13:00-17:00 | Writing a reproducible report using Markdown/Quarto |  | Christian Althaus, Alan Haynes, Judith Bouman, Martin Wohlfender

## Slides

You can download all slides [here](https://github.com/ISPMBern/projects-in-R/blob/main/products/slides). If you want to see them in your web browser, click the corresponding link in [Timetable](#timetable).

## Exercises

You can find material for the exercises [here](https://github.com/ISPMBern/projects-in-R/blob/main/products/exercises).

## Data sets

We will use the following data sets during the course:

File | Description | Source | Exercise 
---- | ----------- | ------ | --------
[COVID19Cases_geoRegion.csv](data/raw/COVID19Cases_geoRegion.csv) | Laboratory-confirmed SARS-CoV-2 cases by region | [FOPH](https://idd.bag.admin.ch) | -
[COVID19Cases_geoRegion_AKL10_w.csv](data/raw/COVID19Cases_geoRegion_AKL10_w.csv) | Laboratory-confirmed SARS-CoV-2 cases by region and age group | [FOPH](https://idd.bag.admin.ch) | -
[covid_cantons_2020_06.csv](data/processed/covid_cantons_2020_06.csv) | Laboratory-confirmed SARS-CoV-2 cases for selected cantons and time period | [FOPH](https://idd.bag.admin.ch) | -
[ebola.csv](data/raw/ebola.csv) | World-wide Ebola cases from 2014-2016  | [data.world](https://data.world/brianray/ebola-cases) | 4
[insurance_with_date.csv](data/raw/insurance_with_date.csv) | Data on costs of medical procedures | [kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance?resource=download) | 5

## Further online material

We recommend the following online tutorials and books on R and RStudio with specific applications to epidemiology, public health, and data science:

- [The R Manuals](https://rstudio.github.io/r-manuals/)
- [Hands-On Programming with R](https://rstudio-education.github.io/hopr)
- [The Epidemiologist R Handbook](https://epirhandbook.com/en/)
- [Introduction to R for Public Health Researchers](https://jhudatascience.org/intro_to_r/index.html)
- [R for Data Science](https://r4ds.had.co.nz)
- [Fundamentals of Data Visualization](https://clauswilke.com/dataviz)

## Contact

If you have any questions regarding the course, please get in touch with us at <phs-info.ispm@unibe.ch> or <christian.althaus@unibe.ch>.
