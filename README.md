# Natural Language Processing Implementations

Course projects from the University of Tehran's Natural Language Processing course, organized as reproducible notebooks that progress from classical text processing to neural representation learning.

## Highlights

- Built rule-based, BPE, and WordPiece tokenization workflows for Persian text.
- Implemented N-gram language models with Laplace, backoff, and interpolation smoothing; interpolation reduced validation perplexity to **33.27** in the reported experiment.
- Implemented logistic regression and Naive Bayes classifiers from scratch and evaluated them on spam and phishing-URL detection.
- Implemented CBOW and Skip-gram with negative sampling, then trained a FastText-based neural news classifier that reached **85.8% test accuracy** and **85.75% macro F1**.

## Repository structure

| Module | Topics | Main artifact |
| --- | --- | --- |
| `01-text-processing-and-language-modeling/` | Regex, edit distance, Persian tokenization, N-gram generation and smoothing | `text-processing-tokenization-ngram.ipynb` |
| `02-classical-text-classification/` | Bag-of-words, from-scratch logistic regression and Naive Bayes, URL feature engineering | `classical-text-classification.ipynb` |
| `03-neural-word-embeddings/` | CBOW, Skip-gram, negative sampling, FastText embeddings, MLP classification | `neural-word-embeddings.ipynb` |

Each module keeps its notebook beside the data and saved artifacts it expects. Run a notebook with its module directory as the working directory so relative paths resolve correctly.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter lab
```

Python 3.10 or newer is recommended. Some notebook cells are computationally intensive and benefit from a CUDA-capable PyTorch environment.

## Notes on reproducibility

- Random seeds used by individual experiments are preserved in the notebooks.
- Reported metrics are retained in notebook outputs so results can be reviewed without rerunning long training jobs.
- Saved tokenizers and model checkpoints are included for inspection and downstream evaluation.

## Scope

This repository is an educational portfolio of course implementations. The notebooks contain the original experimental reasoning and results, with presentation boilerplate removed for a cleaner public release.
