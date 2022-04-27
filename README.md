
# Report template

This repository is the report template for the research project. Each
team will have one repo to work on collaboratively using the tools they
have learned as part of the course. Each team member will clone a copy
of the repo to a remote repository using the workspace for the course on
RStudio Cloud.

This document describes:

1.  the Directories & Files of the template repo;
2.  the detailed Grading information for the report;
3.  the plans for Publishing elements of the research project.

# Directories & Files

The repository has the following directory tree.

    .
    ├── 00-main-report.qmd
    ├── 01-introduction.qmd
    ├── 02-methods.qmd
    ├── 03-01-results.qmd
    ├── 03-02-results.qmd
    ├── 03-03-results.qmd
    ├── 04-conclusions.qmd
    ├── 05-recommendations.qmd
    ├── CITATION.cff
    ├── CODE_OF_CONDUCT.md
    ├── LICENSE.md
    ├── README.md
    ├── README.qmd
    ├── data
    │   ├── README.md
    │   ├── raw_data
    │   │   └── README.md
    │   └── tidy_data
    │       ├── README.md
    │       └── metadata
    │           ├── README.md
    │           └── attributes.csv
    ├── research-project-template.Rproj
    └── src
        └── 01-tidy-raw-data.R

The following table presents a brief description of each file and
directory. The contribution column states how contribution is managed
for the individual items.

| name                | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | contribution                        |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------|
| 00-main-report.qmd  | This is the main report. The report uses code-chunks with ‘child documents’ to compile the report with all sections.                                                                                                                                                                                                                                                                                                                                                          | All team members. Self coordinated. |
| 01-introduction.qmd | This is the introduction section for the main report. Comments inside the document provide guidance for content.                                                                                                                                                                                                                                                                                                                                                              | All team members. Self coordinated. |
| 02-methods.qmd      | This is the methods section for the main report. Comments inside the document provide guidance for content.                                                                                                                                                                                                                                                                                                                                                                   | All team members. Self coordinated. |
| 03-01-results.qmd   | This is one of three results sections for the main report. It contains the core data analysis, including all steps of data import, cleaning, transformation, visualisation and tables. It also includes a discussion of the presented results. One file was created for each team member to provide their own individual contribution to the report. Team members coordinate themselves to decide who works in which file.                                                    | Individual team member.             |
| 03-02-results.qmd   | See above: 03-01-results.qmd                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Individual team member.             |
| 03-03-results.qmd   | See above: 03-01-results.qmd                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Individual team member.             |
| 04-conclusions.qmd  | This is the conclusions section for the main report. Comments inside the document provide guidance for content.                                                                                                                                                                                                                                                                                                                                                               | All team members. Self coordinated. |
| 05-recommendations. | This is the recommendations section for the main report. Comments inside the document provide guidance for content.                                                                                                                                                                                                                                                                                                                                                           | All team members. Self coordinated. |
| CITATION.cff        | A citation file in the citation file format (.cff). Names of contributors and their ORCID iD are added to this file.                                                                                                                                                                                                                                                                                                                                                          | All team members. Self coordinated. |
| CODE_OF_CONDUCT.md  | A code of conduct for this project.                                                                                                                                                                                                                                                                                                                                                                                                                                           | None                                |
| LICENSE.md          | A license for this project.                                                                                                                                                                                                                                                                                                                                                                                                                                                   | None                                |
| README.md           | A README.md file compiled from README.qmd with format gfm (GitHub Flavoured Markdown)                                                                                                                                                                                                                                                                                                                                                                                         | None                                |
| README.qmd          | A README.qmd file to write up general information about this project.                                                                                                                                                                                                                                                                                                                                                                                                         | None                                |
| data                | A data directory with sub-directories. Each individual directory contains a README.md with general information about its content. Open the individual README files to access the information.                                                                                                                                                                                                                                                                                 | All team members. Self coordinated. |
| src                 | A source directory, which contains a .R file for data tidying of the raw data. This file is not edited by student team members, but by the course coordinators. Depending on the level of data tidying that is needed to work with the collected raw data, course coordinators may provide some code for data tidying here. The aim is to provide students with a tidy data set as early as possible, so that exploratory analysis using data visualisation can be performed. | Course coordinators.                |

# Grading

The project report is graded in two categories (intellectual and
technical) and contributes a total of 30 points to the final grade (see
following table).

| type    | category     | description                                                                                  | points |
|:--------|:-------------|:---------------------------------------------------------------------------------------------|-------:|
| project | intellectual | This part of the project grades the intellectual framing of the results in the final report. |     15 |
| project | technical    | This part of the project grades the technical parts of the final report.                     |     15 |

## Graded items

The following table is a detailed list of items for grading of the
research project report are presented. Some items are graded for the
team, while items related to the “Results & Discussion” sections of the
report are graded for each individual team member. Individual items make
up 13 points and team items make up 17 of the total points for the
research project report.

| items                                                                                                                                                                                                                                                                                 | points | grading    |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------:|:-----------|
| YAML header of main report has title, authors, table of contents that are correctly displayed in the compiled output.                                                                                                                                                                 |      1 | team       |
| Each results sections has at least two data visualisations.                                                                                                                                                                                                                           |      1 | individual |
| Data visualisations display at least two variables and are readible in a standalone format with edited labels (axis labels, title, legend title). At least one scaling function is applied (e.g. color/fill, axis). A theme is applied. Each visualisation has a label and a caption. |      5 | individual |
| The report includes a table with summary statistics (e.g. mean, median, sd). The table is formatted using a function taught during the course.                                                                                                                                        |      1 | individual |
| The two data visualisations and the table are cross-referenced in the results sections of the report.                                                                                                                                                                                 |      1 | individual |
| Messages and warnings are hidden from the compiled output, but code is shown in the compiled output.                                                                                                                                                                                  |      1 | team       |
| A bibliography with references was exported from the team folder in the Zotero Group rbtl. The bibliography is uploaded to the main directory of the repository and added to the YAML header of the main report file. References are used throughout the report.                      |      1 | team       |
| The results sections of the report contain at least two locations where inline code is used to show single number results.                                                                                                                                                            |      1 | individual |
| Metadata for data contained in the ‘data/tidy_data/’ directory is added using the provided README and CSV file templates.                                                                                                                                                             |      2 | team       |
| Contributor details for all team members are added to the CITATION.cff file.                                                                                                                                                                                                          |      1 | team       |
| Introduction with 3 to 5 references clearly frames the research question and provides justification for the work.                                                                                                                                                                     |      2 | team       |
| Methods are clearly documented and replicable.                                                                                                                                                                                                                                        |      2 | team       |
| Meaning of results are interpreted; how each Figure/Table contributes to answering the main Research Question is explained; Limitations of the data are honest and discussed.                                                                                                         |      4 | individual |
| Conclusions concisely summarize findings in a bullet point format.                                                                                                                                                                                                                    |      3 | team       |
| Recommendations for future work are provided.                                                                                                                                                                                                                                         |      4 | team       |

# Publishing

The goal is to publish all elements of the research reports after
students have received their final grades (including the exam) and the
data and results were shared and presented to Stadt Zürich, Entsorgung
and Recycling (ERZ) team.

## Data

The tidy data from all students projects will be compiled in one central
data repository and published for long-term archiving using Zenodo
publishing service to generate a Digital Object Identifier (DOI). This
in return will be added to the CITATION.CFF file contained in
`research-project-template`. Together with the a persistent digital
identifier (an ORCID iD) credit is attributed to all contributors.

## Scientific journals

The course coordinators are planning to publish in scientific journals.
This could be a journal related to Waste Management where actual data
and results are used. This could also be a journal related to the
educational format of this course. Independent of where course
coordinators decide to publish, the goal is to add all contributors as
co-authors to the manuscript. If that is not possible, at the least, all
contributors will be added with their individual contributions to
research design, data collection, and analysis using the [CRediT
(Contributor Roles Taxonomy)](https://casrai.org/credit/).

## Student’ portfolios

If all team members of each group agree, then the repository for the
research project report can be forked by individual team members to
their personal GitHub Account, made public and published using GitHub
Pages or another free service (e.g. Netlify). Doing this will help
students build a portfolio on GitHub and showcase the work they have
done as part of the course.
