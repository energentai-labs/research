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
   - Remove the punctuation, but keep the hyphens.
   - Use lowercase letters.
   - Put one hyphen between two words.

   For example, "What Production Reveals That Leaderboards Can't" gives `what-production-reveals-that-leaderboards-cant`.
2. Make the folder `papers/<folder-name>/`.
3. Compile the PDF from the LaTeX source. Do not use the PDF from an arXiv submission. That PDF has a stamp in the margin.
4. Put the PDF in the folder. Use the folder name as the PDF name.
5. Copy `index.html` from a different paper folder into the new folder.
6. In the new `index.html`, replace each instance of the old folder name and the old title.
7. Replace the authors, the year, the description, the abstract, and the BibTeX entry.
8. In `README.md`, add the paper to the "Papers" table.
9. In `README.md`, add the BibTeX entry of the paper to "Cite a paper".
10. In `CITATION.cff`, replace `preferred-citation` with the data of the new paper.
11. Merge the change into `main` with a pull request. GitHub Pages then publishes the web page.
12. Open the web page. Make sure that the PDF link and the BibTeX entry are correct.

## Update a paper

Do not change the folder name or the title. If you change the folder name, the links to the paper do not work. Google Scholar uses the title to show all versions of the paper as one article.

If the PDF changes, replace the PDF. Keep the same file name.

If arXiv publishes the paper, do these steps:

1. Add the arXiv link to the web page and to the "Papers" table.
2. In the BibTeX entries in `index.html` and `README.md`, add `eprint = {<arXiv ID>}` and `archivePrefix = {arXiv}`.
3. If the paper is in `CITATION.cff`, add the arXiv link under `identifiers` in `preferred-citation`.

## Show a paper on Google Scholar

Google Scholar finds a paper from its web page. The `citation_*` tags in `index.html` give Google Scholar the title, the authors, the date, and the address of the PDF. It can be some weeks before Google Scholar finds a new paper. It is possible that Google Scholar does not find a paper.

To show a paper on an author profile before Google Scholar finds it, do these steps:

1. On the Google Scholar profile, click "+".
2. Click "Add article manually".
3. Type the exact title, the authors, and the year.
4. Click "Save".
5. When Google Scholar finds the paper, make sure that the paper is on the profile.
6. Select the two articles of the paper on the profile.
7. Click "Merge".
