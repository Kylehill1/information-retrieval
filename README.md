# Information Retrieval: From Theory to Implementation

A Jupyter notebook implementing core Information Retrieval models from scratch in Python — no external IR libraries used.

Built as part of coursework at **Kennesaw State University**.

## Models Implemented

| Model | Description |
|---|---|
| Boolean Retrieval | Inverted index with AND/OR query logic |
| Unigram Language Model | Bag-of-words probability over a corpus |
| Bigram Language Model | Conditional word probabilities capturing local order |
| TF-IDF | Term frequency × inverse document frequency ranking |
| BM25 | Industry-standard ranking with TF saturation and length normalization |
| Query Likelihood | Probabilistic ranking via P(query \| document model) with Laplace smoothing |

## Getting Started

### Requirements
- Python 3.7+
- Jupyter Notebook or JupyterLab

### Installation

```bash
git clone https://github.com/YOUR_USERNAME/information-retrieval.git
cd information-retrieval
pip install notebook
jupyter notebook information_retrieval.ipynb
```

## Usage

Run each cell top to bottom. The final cells let you enter your own queries and compare how all models rank the same corpus side by side.

## Key Concepts

- **Inverted Index** — the backbone of Boolean and ranked retrieval
- **TF-IDF** — balances how common a term is in a doc vs. how rare it is across the corpus
- **BM25 k1 parameter** — controls TF saturation (diminishing returns for repeated terms)
- **BM25 b parameter** — controls document length normalization
- **Laplace Smoothing** — prevents zero probabilities in the Query Likelihood model

## Author

Kyle Hillhouse — [Hillhouse.kyle@gmail.com](mailto:Hillhouse.kyle@gmail.com)
