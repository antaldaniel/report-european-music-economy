# Report on the European Music Economy

This repo is created two deliverable. This deliverable is preceded by [Music Economy: Methods & Indicators](https://github.com/dataobservatory-eu/music_economy_methods_indicators/).

1. [Report on the European Music Economy](https://zenodo.org/record/6464782#.Ylq7JNpBzIU) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6464782.svg)](https://doi.org/10.5281/zenodo.6464782). Follow the creation of this deliverable here:

-    T1.1. [Economy of music in Europe: Novel data collection methods and indicators](https://music.dataobservatory.eu/documents/open_music_europe/economy/report/report.html)
-   T1.2 Not yet started
-   T1.3 Not yet started

2. [Economy of music in Europe: Novel data collection methods and indicators](https://doi.org/10.5281/zenodo.6464990) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6464990.svg)](https://doi.org/10.5281/zenodo.6464990)

Both follow the [Open Policy Analysis Guidelines](http://www.bitss.org/wp-content/uploads/2019/03/OPA-Guidelines.pdf) and the best practices of the European Union's Knowledge For Policy and the [European Open Science Cloud](https://eosc-portal.eu/) portal.

## Main files

The [Economy of music in Europe: Novel data collection methods and indicators]() document's files are available as follows: 
- The working source document is `report_muisc_europe_data_collection.qmd`. It can be opened with any text editor but best viewed with a markdown editor or Posit's free data science editor RStudio. 
- The rendered versions (may not be in minute-to-minute sync with the source document) are in the `docs/` folder: `port_muisc_europe_data_collection.html` and `.epub` and `.docx` and `.pdf`
- The versions approved by the Work Package Leader are available under separate (versioned) DOI on the European Open Science long-term repository Zenodo in the Digital Music Observatory collection, click below on the DOI number or look it up in your browser:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6464782.svg)](https://doi.org/10.5281/zenodo.6464782)


` `: The working source document of the [Data coordination and indicator methodology for Open Music Europe]() auxiliary document for _Novel data collection methods and indicators_.  The rendered versions (may not be day-to-day in sync with the source document) are in `docs/report_muisc_europe_data_collection.html` and `.epub` and `.docx` and `.pdf`
- The rendered versions (may not be in minute-to-minute sync with the source document) are in the `docs/` folder: [economy_music_data_indicators.html]([pdf](https://github.com/antaldaniel/report-european-music-economy/raw/main/docs/economy_music_data_indicators.html)), [epub](https://github.com/antaldaniel/report-european-music-economy/raw/main/docs/economy_music_data_indicators.epub), [pdf](https://github.com/antaldaniel/report-european-music-economy/raw/main/docs/economy_music_data_indicators.pdf),

`_quarto.yml`: Some metadata on how to render the source files. For reference see [Quarto Project Basics](https://quarto.org/docs/projects/quarto-projects.html).

## Folders

**root** - The two articles, `.bib` bibliography files, and `yml` files for markdown conversions, plus reproducbile `docx`, `pdf`, `epub` versions. Work in the `Rmd` markdown files. If you do not write R code, just ignore the R code chunks, and use it as a clean markdown text.

**bib** - The bibliographic references in BibTex entries are organised into `bib/xyz.bib` text files.  For example, `bib/musicindustry.bib` contains references about the definition of the Music Industry, or `bib/openscience.bib` about the use of Open science sources.

**not_included** - user's scrap directory, excluded by `.gitignore`.  Please put your non-synchronized scaps and code doodles here.

**data-raw** - data as downloaded, received, as a starting point of our reproducible work. You will find here 5 CAP surveys.

**R** - R code written for the publications.  It is better to write stand-alone R codes, and put final 'chunks' into the `.Rmd` files.

**Py** - You can use optionally Python files.  Posit (formerly RStudio) can weave R, C++ and Python elements into the documents.

**data** - Final data outputs that will be placed in the articles.

`_book`: Research output in PDF/EPub/Docx files.  For each output, start a new repository. All our deliverable are delivered in a version-controlled repository. 
`png`: Portable Network Graphics visualizations.
`jpg`:
`R`: R language code that produces the spreadsheets or visualizations or tables.

## OPA Open Materials

From the [Open Policy Analysis Guidelines](http://www.bitss.org/wp-content/uploads/2019/03/OPA-Guidelines.pdf):

- Label and document each input, including data, research, and guesswork: see contents of documents.

- Standardize the file structure so that materials are organized in a way that is accessible to an informed reader: see below folder documentation.

- Ensure that code/spreadsheets are reproducible. 

- All research and innovation team members use version control software and track changes in a shared project repository. It is clear who contributed to the research, when, and who approved or rejected the contribution.

## Citations, assets, bibliography

The bibliography files (`*.bib` files) can be found in the open repository of the [Report on the European Music Economy](https://github.com/dataobservatory-eu/european_music_economy) (main folder.)

The used references are at the end of the report.

-   `ceemid.bib`: The background results of the former [CEEMID project](https://reprex.nl/project/ceemid/).
-   `caselaw.bib`: Jurisprudence and cases reviewed for this report.
-   `cci.bib`: Cultural and creative industries studies relevant for the music industry.
-   `competition.bib`: Relevant competition policy sources for the music economy.
-   `copyrightlaw.bib`: Relevant copyright laws for the economic valuations.
-   `ifpi.bib`: Publications of IFPI.
-   `ifrs.bib`:  International Financial Reporting Standards and their adoption to EU or national laws.
-    `ILO.bib`: Documents, treaties and recommendations of the International Labor Organization.
-    `indicators.bib`: Methodology of creating public policy or business indicators.
-    `figures.bib`:  Figures cited in this report.
-    `mixedsurveys.bib`:  Mixed (household/enterprise) surveys.
-   `musicindustry.bib`:  Studies on the music industry and its value creation.
-    `OpenMuse.bib`:  Documents related to the Open Music Europe project.
-    `openmusicrepositories.bib`:  References to the Open Policy Analysis Guidelines compatible repositories of the `Open Music Europe` project.
-    `opendata.bib`:  Open data references.
-    `openscience.bib`:  Open science references.
-    `ossh.bib`: Open source software and hardware references.
-    `policyevidence`:  References on evidence-based policies.
-   `precarious.bib`: References on the informal economy or precarious work.
-   `mme.bib`: Music moves Europe references.
-   `slovakia.bib`: Slovak language and Slovakia specific references.
-   `statreg.bib`: Statistical regulations.
-    `valuation.bib`: 
-    `wipo.bib`:  Treaties and publications of the [World Intellectual Property Organization](https://www.wipo.int/).

## Links

See the deliverable legal description [here](https://openmuse.dataobservatory.eu/resources/music-economy/) and the results on the [music.dataobservatory.eu](https://music.dataobservatory.eu/) website; currently this is a document that is work in progress here: [Economy of music in Europe: Novel data collection methods and indicators](https://music.dataobservatory.eu/documents/open_music_europe/economy/report/report.html).
