# llm-mechanisms

Hands-on notebooks for building intuition about core language-model mechanics from first principles.

This repository currently focuses on a minimal text-processing pipeline:

- tokenization
- lexicon / vocabulary construction
- token-to-index and index-to-token mappings
- encoding and decoding text sequences
- simple token visualization
- local context inspection around target tokens

## Repository layout

- `notebooks/`
  Reference walkthroughs and explanatory material.
- `exercises/`
  Practice notebooks that turn the concepts into working code.

## Current notebooks

- `notebooks/tokenization-lexicon-construction-and-index-mapping.ipynb`
  Introduces parsing raw text into tokens, building a lexicon, and mapping tokens to integer indices.
- `exercises/token-encoding-decoding-visualization-and-context-analysis.ipynb`
  Implements encoding and decoding, visualizes token indices, and inspects token context in a small corpus.

## Environment

Python `>=3.13`

Install the minimal dependencies with:

```bash
pip install -r requirements.txt
```

Launch Jupyter and open the notebooks:

```bash
jupyter notebook
```

## Scope

The goal of this repo is not to provide a full tokenizer library. It is a compact learning workspace for understanding the discrete representations that underpin language-model pipelines.
