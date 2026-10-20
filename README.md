# Energent.ai Labs Research

This repository contains the research papers of Energent.ai Labs. Energent.ai Labs is the research team of [Energent.ai](https://energent.ai).

Each paper has a PDF and a web page. The web site is [energentai-labs.github.io/research](https://energentai-labs.github.io/research/).

## Papers

| Year | Paper | Authors |
| --- | --- | --- |
| 2026 | [What Production Reveals That Leaderboards Can't](https://energentai-labs.github.io/research/papers/what-production-reveals-that-leaderboards-cant/) ([PDF](papers/what-production-reveals-that-leaderboards-cant/what-production-reveals-that-leaderboards-cant.pdf)) | Lingjie Kong, Rachel Hu |

## Cite a paper

Cite the paper, not this repository. Copy the BibTeX entry of the paper:

```bibtex
@techreport{kong2026production,
  title       = {What Production Reveals That Leaderboards Can't},
  author      = {Kong, Lingjie and Hu, Rachel},
  institution = {Energent.ai},
  year        = {2026},
  url         = {https://energentai-labs.github.io/research/papers/what-production-reveals-that-leaderboards-cant/}
}
```

The "Cite this repository" button on GitHub gives the citation of the newest paper. The `CITATION.cff` file controls this button.

## Add a paper

Each paper has one folder in `papers/`. The folder name and the PDF name come from the exact title of the paper:

```text
papers/
└── what-production-reveals-that-leaderboards-cant/
    ├── what-production-reveals-that-leaderboards-cant.pdf
    └── index.html
```

To add a paper, do these steps:

1. Make a folder name from the exact title of the paper:
   - Use lowercase letters.
   - Put a hyphen between the words.
   - Remove the punctuation.
2. Make the folder `papers/<folder-name>/`.
3. Put the PDF in the folder. Use the folder name as the PDF name.
4. Copy `index.html` from a different paper folder into the new folder.
5. In the new `index.html`, replace the data of the old paper with the data of the new paper. This includes the `citation_*` tags and the BibTeX entry.
6. Add the paper to the "Papers" table in this file.
7. Add the BibTeX entry of the paper to "Cite a paper".
8. In `CITATION.cff`, replace `preferred-citation` with the data of the new paper.

## Update a paper

A paper can get a new version, for example an arXiv version. To update a paper, do these steps:

1. Replace the PDF. Keep the same file name.
2. Add the new link (for example, the arXiv link) to the web page, to the "Papers" table, and to the BibTeX entry.

Do not change the folder name or the title. If you change the folder name, the links to the paper stop working. Google Scholar uses the title to put all versions of the paper into one entry.

## Show a paper on Google Scholar

Google Scholar finds a paper from its web page. The `citation_*` tags in `index.html` give Google Scholar the title, the authors, the date, and the address of the PDF. Google Scholar can need some weeks to find a new paper. It is possible that Google Scholar does not find a paper.

To show a paper on an author profile before Google Scholar finds it, do these steps:

1. On the Google Scholar profile, click "+".
2. Click "Add article manually".
3. Type the exact title, the authors, and the year.
4. When Google Scholar finds the paper, select the two entries on the profile.
5. Click "Merge".
