# Create a Question Bank
🙋‍♀️ Creating multi-language glossaries for information and collections management, and digital humanities.

🌈 Contribution guidelines - you must abide by the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) Code of Conduct.

## Source files
`QB_paper.qmd`: abbreviations and definitions on artificial intelligence (AI) which can be previewed in [docs/QB_paper.md](https://github.com/dataobservatory-eu/questionbank_papers/blob/main/docs/QB_paper.md).


## Rendered files

The edited files are rendered to `docs/`, which is _not synchronized_ to GitHub (see `.gitignore`) with the exception of `md` markdown files that can be read on GitHub, see for example 

## Ignored files in .gitignore
The `.gitignore` file contains file names, bulk file name exceptions, and entire folders that are *not* to be synchronized to GitHub.

`not_included`: serves as the place of your personal scrapbook, sandbox, that you do not want to share with anybody.

`docs`: the final,  edited texts (we do not synch because if the `qmd` file is correct, they should work with all users of the shared repository.)

## Referencing and attribution

`bib`: Contains all bibliography: used citations, data used, visualisation used, datasets created, visualizations created, public text document outputs created.
`bib/ddi.bib`: Referencing DDI-related material
`bib/cm.bib`: Conceptual models: CIDOC, RiC, EDM.
`bib/r_packages.bib`: Referencing R packages.
`bib/OpenMusE.bib`: Referencing EU-funded outputs.
`bib/wikidata.bib`: Uses of Wikidata for various use cases.

## Data folders

We have two data folders, which may have numerous subfolders.

`data-raw`:  Raw, unprocessed data, as received, downloaded, collected. You can place here small PDF files if when necessary.

`data`: This folder contains the processed data or our outputs.  Any data here must adhere to the tidy data principle and be documented by DataCite standards.  We are developing a tool, dataset, which will do this automatically in WP4.  We can investigate a Python connector for this if there is a need for that.

## Visualisation folders

We save visualisations in folders corresponding to the file format. This is the best way to ensure that pandoc or any compiles has the necessary plugins to work with the visualizations. Every visualization that is intended to made pubic gets a bibliographic citation and a globally unique DOI identifier. 

`png`: contains visualisations in Portable Network Graphics format (our preferred format.)

`jpg`: Contains visualization in Joint Photographic Experts Group format.

`webp`: Contains visualisations in WebP is an open image file format developed by Google intended as a replacement for JPEG, PNG, and GIF file formats.  We prefer this for content intended for web use (presentations, blogposts), because it works much faster and better with browsers than PNG or JPG.

[…] You can use other formats if necessary.


## Other file formats

`docx`: Word documents.  Whenever possible, use small files, and only for templating.
