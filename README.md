# Journal of Multivariate Analysis — Author Guide Resources

> This project is a companion for authors preparing manuscripts for the *Journal of Multivariate Analysis* (JMVA) maintained by the journal editors.

## Repository purpose

This repository provides a practical starting point for preparing, checking, and packaging manuscripts for JMVA. It is intended to collect:

- concise notes from the official Guide for Authors;
- LaTeX manuscript templates using Elsevier CAS style;
- optional Word/cover-letter/checklist templates;
- scripts for compiling, cleaning, and packaging submissions;
- reproducibility guidance for code, data, figures, and supplementary material;
- contact and support links for contributors and authors.

The repository should be treated as a supplement of the official author instructions. Journal policies, submission workflows, article processing charges, LaTeX requirements, and editorial contacts may change.

## JMVA requirements summarized

The following is a brief, paraphrased checklist for convenience. Confirm details with the official guide before submitting.

- **Scope:** JMVA publishes new methodology and theoretical developments in multivariate statistics, with innovative applications related to multidimensional data analysis.
- **Typical article length:** JMVA notes that an article is generally **15–25 pages**.
- **Proofs:** Proofs of propositions, theorems, and lemmas should appear in the main text or an appendix, not only in supplementary material.
- **Review model:** The journal uses a single-anonymized peer-review process.
- **Source files:** Editable source files are required. Use `.tex` for LaTeX submissions or `.doc/.docx` for Word submissions. A PDF alone is not an acceptable source file.
- **Abstract:** Keep the abstract concise, factual, and no more than **250 words**.
- **Keywords:** Provide **1–7 keywords** in English.
- **Highlights:** Highlights are encouraged. Use **3–5 bullet points**, each no more than **85 characters including spaces**, and submit them as a separate editable file.
- **Tables:** Submit tables as editable text rather than images.
- **Figures:** Submit graphical files separately, use logical file names, cite each figure in the text, and provide captions.
- **Research data:** Authors are encouraged to deposit research data in a relevant repository and cite datasets in the article.
- **References:** At initial submission, references may use any consistent style, but required bibliographic details and DOIs should be included where available.
- **Generative AI:** Any use of generative AI or AI-assisted tools in manuscript preparation must be declared when required by Elsevier policy.


## Templates

### LaTeX templates

This repository is designed for Elsevier CAS-style LaTeX submissions.

Recommended template folders:

- `templates/cas-sc/` — single-column CAS manuscript template using `cas-sc.cls`.
- `templates/cas-dc/` — double-column CAS manuscript template using `cas-dc.cls`.
- `templates/cas-sc/references.bib` — sample BibTeX database.
- `templates/cas-sc/highlights.tex` — separate highlights file.

## Submission package checklist

Before submitting through the official JMVA submission portal, check that the package includes:

- main manuscript source file, for example `main.tex`;
- bibliography file, for example `references.bib` or generated `.bbl` if required;
- all required `.cls`, `.sty`, and `.bst` files not provided by the submission system;
- figure files in accepted formats such as PDF, EPS, PNG, JPG, or TIFF;
- separate highlights file, if provided;
- supplementary files, if any;
- declarations, acknowledgements, funding statement, competing-interest statement, data-availability statement, and AI-use statement where applicable;
- no duplicate base file names with different extensions;
- no problematic special characters in file names;
- no subdirectories in the final Editorial Manager upload package.

## Reproducibility guidance

For manuscripts with computational results, include enough information for reviewers and readers to understand the workflow:

- software versions;
- random seeds;
- simulation settings;
- data sources and access instructions;
- scripts used to generate tables and figures;
- a clear relationship between manuscript results and repository files.

Do not commit confidential data, identifiable human-subject data, licensed datasets, credentials, or large generated files unless the repository policy and data license allow it.

## Contributing

- Contributions are welcome if they improve manuscript preparation, reproducibility, or documentation clarity.

- Please avoid copying large portions of Elsevier documentation. Summarize requirements in your own words and link to the official source.

## Official sources

For editorial decisions, manuscript status, technical upload problems, copyright questions, publication delays, or proof corrections, contact Elsevier or the journal through the official submission/support channels rather than this repository. 

- [JMVA Guide for Authors on ScienceDirect](https://www.sciencedirect.com/journal/journal-of-multivariate-analysis/publish/guide-for-authors)
- [JMVA journal homepage on ScienceDirect](https://www.sciencedirect.com/journal/journal-of-multivariate-analysis)
- [Submit to JMVA](https://submit.elsevier.com/JMVA)
- [Elsevier LaTeX instructions](https://www.elsevier.com/researcher/author/policies-and-guidelines/latex-instructions)
- [Elsevier support: submitting LaTeX files in Editorial Manager](https://www.elsevier.support/publishing/answer/how-to-submit-a-latex-file-in-editorial-manager)
- [Elsevier Journal Article Publishing Support Center](https://service.elsevier.com/)


## Disclaimer

This repository is provided for convenience only. It may contain errors.
