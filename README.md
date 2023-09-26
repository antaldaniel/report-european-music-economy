# Report on the European Music Economy

-    T1.1. _Economy of music in Europe: Novel data collection methods and indicators_. The [website view](https://music.dataobservatory.eu/documents/open_music_europe/economy/report/report.html) has the latest [not reviewed] working version with epub, PDF downloads on the rigth hands side. This is updated whenever there is a significant change in the document. The authoritative copies can be found on Zenodo, the European open science repository for long-term archiving and linking, citing 
[in pdf, docx, epub](https://doi.org/10.5281/zenodo.8334648) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8334648.svg)](https://doi.org/10.5281/zenodo.8334648). The authoritative copy is updated at significant changes and after internal or external quality control steps.
-   T1.2 Not yet started
-   T1.3 Not yet started

The tasks follow the [Open Policy Analysis Guidelines](http://www.bitss.org/wp-content/uploads/2019/03/OPA-Guidelines.pdf) and the best practices of the European Union's Knowledge For Policy and the [European Open Science Cloud](https://eosc-portal.eu/) portal.

## How to contribute?

- We have a [Contributor's Handbook](https://manual.dataobservatory.eu/).
- Make sure you __fork__ this repository (i.e., create an own copy for yourself, see [Introduction to GitHub](https://manual.dataobservatory.eu/)) and do not try to work in the master joint repository. 
- Create a `not_included/` subfolder in your local copy if you want a sandbox for your doodles and unfinished work. They will be excluded by `.gitignore`, i.e., they will never leave your computer.
-  🌈 you must abide by the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) Code of Conduct.

## Main files
The [Economy of music in Europe: Novel data collection methods and indicators](https://music.dataobservatory.eu/documents/open_music_europe/economy/report/report.html) document's files are available as follows: 
- The working source document is `report_muisc_europe_data_collection.qmd`. It can be opened with any text editor but best viewed with a markdown editor or Posit's free data science editor RStudio. 
- The rendered versions which are easier to read (but may not be in minute-to-minute sync with the source document) are in the `docs/` folder: [report_music_europe_data_collection.html](https://github.com/antaldaniel/report-european-music-economy/raw/main/docs/report_music_europe_data_collection.html) and [epub](https://github.com/antaldaniel/report-european-music-economy/raw/main/docs/report_music_europe_data_collection.epub), [docx](https://github.com/antaldaniel/report-european-music-economy/raw/main/docs/report_music_europe_data_collection.epub), [pdf](https://github.com/antaldaniel/report-european-music-economy/raw/main/docs/report_music_europe_data_collection.pdf)
- The versions approved by the Work Package Leader are available under separate (versioned) DOI on the European Open Science long-term repository Zenodo in the Digital Music Observatory collection, click below on the DOI number or look it up in your browser:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8334648.svg)](https://doi.org/10.5281/zenodo.8334648)


The working auxiliary document _Data coordination and indicator methodology for Open Music Europe_ became part of the [Data Pillars in the Open Music Observatory](https://zenodo.org/record/8108720) document.
- The working source document is `economy_music_data_indicators.qmd`. It can be opened with any text editor but best viewed with a markdown editor or Posit's free data science editor RStudio. 
- The rendered versions which are easier to read (but may not be in minute-to-minute sync with the source document) are in the `docs/` folder: [economy_music_data_indicators.html](https://github.com/antaldaniel/report-european-music-economy/raw/main/docs/economy_music_data_indicators.html), [epub](https://github.com/antaldaniel/report-european-music-economy/raw/main/docs/economy_music_data_indicators.epub), [pdf](https://github.com/antaldaniel/report-european-music-economy/raw/main/docs/economy_music_data_indicators.pdf),

`_quarto.yml`: Some metadata on how to render the source files. For reference see [Quarto Project Basics](https://quarto.org/docs/projects/quarto-projects.html).

## Presentation

`presentations/` folder: Stand-alone presentation files related to the main report.
- [presentations/Open_Music_Europe_Slovakia_20230921.pptx](https://github.com/dataobservatory-eu/report-european-music-economy/raw/main/presentations/Open_Music_Europe_Slovakia_20230921.pptx): the presentation slides for the Slovak national stakeholder consultation held on 21 September 2023. 

## Graphics

`plots/` folder: Illustrations used in the documents in `png` or `jpeg` formats.

## Background documents

- `older-versions/`  A folder with older versions of the manuscripts.  You can see the older versions that had been approved by the Work Package leader on Zenodo under separate (versioned) DOIs.

- `slovak-policy-documents/`: A folder to contain Slovak policy documents which may not be available easily.

- `survey-documentation/`: Questionnaires and other background documents of the surveys mentioned in the main files.

## Unprocessed and Processed Data 
`data-raw/` - data as downloaded, received, as a starting point of our reproducible work. 
`data/` - data that has been processed for the new work.

## Document Templates
`docsx/` - templat for rendering into a Word document.

## Program files
_Not yet present in this project task_
`R/` - R code written for the publications.  It is better to write stand-alone R codes, and put final 'chunks' into the `.Rmd` files.
`Py/` - You can use optionally Python files. 


## Citations, assets, bibliography

`bib/` folder: The bibliographic references in BibTex entries are organised into `bib/xyz.bib` text files.  For example, `bib/musicindustry.bib` contains references about the definition of the Music Industry, or `bib/openscience.bib` about the use of Open science sources.

The bibliography files (`*.bib` files) can be found in the open repository of the [Report on the European Music Economy](https://github.com/dataobservatory-eu/european_music_economy) (main folder.)

The used references are at the end of the report.

-   `bib/ceemid.bib`: The background results of the former [CEEMID project](https://reprex.nl/project/ceemid/).
-   `bib/caselaw.bib`: Jurisprudence and cases reviewed for this report.
-   `bib/cci.bib`: Cultural and creative industries studies relevant for the music industry.
-   `bib/competition.bib`: Relevant competition policy sources for the music economy.
-   `bib/copyrightlaw.bib`: Relevant copyright laws for the economic valuations.
-   `bib/ifpi.bib`: Publications of IFPI.
-   `bib/ifrs.bib`:  International Financial Reporting Standards and their adoption to EU or national laws.
-    `bib/ILO.bib`: Documents, treaties and recommendations of the International Labor Organization.
-    `bib/indicators.bib`: Methodology of creating public policy or business indicators.
-    `bib/figures.bib`:  Figures cited in this report.
-    `bib/mixedsurveys.bib`:  Mixed (household/enterprise) surveys.
-   `bib/musicindustry.bib`:  Studies on the music industry and its value creation.
-    `bib/OpenMuse.bib`:  Documents related to the Open Music Europe project.
-    `bib/openmusicrepositories.bib`:  References to the Open Policy Analysis Guidelines compatible repositories of the `Open Music Europe` project.
-    `bib/opendata.bib`:  Open data references.
-    `bib/openscience.bib`:  Open science references.
-    `bib/ossh.bib`: Open source software and hardware references.
-    `bib/policyevidence`:  References on evidence-based policies.
-   `bib/precarious.bib`: References on the informal economy or precarious work.
-   `bib/mme.bib`: Music moves Europe references.
-   `bib/slovakia.bib`: Slovak language and Slovakia specific references.
-   `bib/statreg.bib`: Statistical regulations.
-    `bib/valuation.bib`: 
-    `bib/wipo.bib`:  Treaties and publications of the [World Intellectual Property Organization](https://www.wipo.int/).


## OPA Open Materials

From the [Open Policy Analysis Guidelines](http://www.bitss.org/wp-content/uploads/2019/03/OPA-Guidelines.pdf):

- Label and document each input, including data, research, and guesswork: see contents of documents.

- Standardize the file structure so that materials are organized in a way that is accessible to an informed reader: see below folder documentation.

- Ensure that code/spreadsheets are reproducible. 

- All research and innovation team members use version control software and track changes in a shared project repository. It is clear who contributed to the research, when, and who approved or rejected the contribution.
