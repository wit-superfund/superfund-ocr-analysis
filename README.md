# AI-Assisted OCR and Analysis of EPA Superfund Documents

This project builds a clean, searchable corpus from EPA Superfund PDFs using AI-assisted OCR, then compares
(1) traditional sentiment analysis methods with (2) LLM-based interpretive analysis (tone, stance, rhetorical positioning)
on technical, bureaucratic environmental policy texts.

**Poster/project page:** [link will appear here after GitHub Pages is enabled]

## Goals
- Build a scalable OCR + text-cleaning pipeline for federal PDF documents
- Create a searchable corpus with consistent metadata
- Compare sentiment baselines (e.g., VADER / logistic regression / transformer sentiment) vs. LLM interpretive labeling
- Document where older sentiment tools fail on jargon-heavy, emotionally-muted text

## Repository layout
- `docs/` — project page (GitHub Pages)
- `src/` — core pipeline code
- `scripts/` — command-line helpers for batch processing
- `notebooks/` — experiments and analysis
- `data_sample/` — small sample files (no large PDFs)
- `outputs/` — generated artifacts (excluded or minimized)

## Data
We do not store the full Superfund corpus in this repo. See `data_sample/README.md` for how to obtain documents and
expected folder structure.

## How to run (placeholder)
1. Create environment: `pip install -r requirements.txt`
2. Run OCR: `python scripts/run_ocr.py --input ... --output ...`
3. Build corpus: `python scripts/build_corpus.py`
4. Run analysis: `python scripts/run_models.py`

## Team
- [Name], Humanities
- [Name], Computing/Data Science
- [Student Name]

## License
MIT (see LICENSE).
