# Preprint Package

This folder is the cleaner, submission-shaped version of the current technical report.

It is meant to be the working package for:

- Zenodo
- OSF Preprints
- SSRN
- later arXiv adaptation

Contents:

- `paper.md` for the manuscript
- `abstract.txt` for submission forms
- `author-bio.txt` for short profile boxes
- `cover-note.txt` for repositories or preprint forms that ask for context
- `keywords.txt`
- `paper.bib` as the current bibliography for the draft
- `submission-metadata.json` as a compact source of reusable metadata
- `zenodo-upload-checklist.md` for the first public posting route
## Repository Health
This repository includes a dependency-free health check for core documentation, metadata, and CI wiring. Run it locally before publishing changes:

```sh
python3 scripts/check_repository_health.py
```

The same check runs in GitHub Actions on pushes and pull requests.
