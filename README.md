# applied-linear-algebra

Notebooks and code exploring applied linear algebra concepts (embeddings, dot products, cosine similarity, etc.).

## Setup

Uses [uv](https://docs.astral.sh/uv/) for dependency management.

```bash
uv sync
```

## Running the notebooks

```bash
uv run jupyter lab
```

Pretrained word vectors are downloaded on first use via `gensim.downloader` and cached in `~/gensim-data`.
