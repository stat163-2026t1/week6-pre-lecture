# STAT163 — Week 6 notebooks: data formats

Two notebooks to work through this week. Nothing to submit.

| Notebook | Time |
|---|---|
| `01-before-the-lecture-data-formats.ipynb` | 50 min |
| `02-before-the-practice-apis-and-json.ipynb` | 30 min |

## Run them with nothing to install

[![Open the first notebook in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stat163-2026t1/week6-pre-lecture/blob/main/01-before-the-lecture-data-formats.ipynb) `01-before-the-lecture-data-formats.ipynb`

[![Open the second notebook in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stat163-2026t1/week6-pre-lecture/blob/main/02-before-the-practice-apis-and-json.ipynb) `02-before-the-practice-apis-and-json.ipynb`

**What Colab is.** Google Colab is a Jupyter notebook that runs in your browser, on a
computer at Google, instead of on your laptop. The cells, the order you run them in, and
pandas all work the way they do in a notebook on your laptop.

Two differences from a notebook on your laptop:

- **The computer at Google is temporary.** When you close the tab, it is gone, with the
  files the notebook writes. The notebook file in this repository does not change. To keep
  your edits, use **File → Save a copy in Drive**.
- **You cannot open the files on your laptop from it.** Here that does not matter: the
  data for these notebooks comes from the web, and you need no other file.

## Or run it on your machine

You need [`uv`](https://docs.astral.sh/uv/) and [Git](https://git-scm.com/downloads).

```bash
git clone https://github.com/stat163-2026t1/week6-pre-lecture.git
cd week6-pre-lecture
uv sync
```

Then open the notebooks in [Positron](https://positron.posit.co/) and, when it asks which
Python to use, choose the one inside `.venv`. Or run `uv run jupyter lab`.
