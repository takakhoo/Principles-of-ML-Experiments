# Principles of Machine Learning: From-Scratch Experiments

A portfolio of course laboratories that develops core machine-learning methods
from first principles. The notebooks emphasize mathematical derivation,
implementation choices, and evaluation rather than high-level estimator APIs.

> This repository is a personal GitHub Classroom fork. Assignment prompts are
> retained for context; the notebooks and submitted artifacts document the
> completed experimental work.

## Portfolio map

| Lab | Topic | Main artifact |
| --- | --- | --- |
| 1 | Sequential prediction and model evaluation through rock–paper–scissors | `assignment1/assignment-1.ipynb` |
| 2 | Linear regression from scratch on Detroit homicide data | `assignment2/assignment2.ipynb` |
| 3A | Sparse autoencoders and learned representations | `assignment3/part 3A/lab03A.ipynb` |
| 3B | Character-level Transformer language modeling on Tiny Shakespeare | `assignment3/part 3B/lab3B.ipynb` |
| 4 | Kernel SVMs with one-vs-one and one-vs-rest multiclass voting | `assignment 4/assignment4.ipynb` |
| 5 | Binary image restoration with a pairwise MRF | `assignment5/assignment5.ipynb` |

## Skills demonstrated

- Translating mathematical objectives into NumPy/PyTorch implementations
- Designing and evaluating controlled experiments
- Regression, representation learning, Transformers, SVMs, and graphical models
- Hyperparameter analysis, confusion matrices, and visual diagnostics
- Communicating design decisions in notebooks and short technical reports

## Getting started

Each lab has its own README and notebook. Start from that lab's directory because
several notebooks use relative data paths.

```bash
git clone https://github.com/takakhoo/Principles-of-ML-Experiments.git
cd Principles-of-ML-Experiments
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
python -m pip install -r requirements.txt
jupyter lab
```

GPU support is optional for most labs but useful for the Transformer experiment.
The original environment details for that lab remain in
`assignment3/part 3B/environment.yml`.

## Academic context

The repository contains coursework and should be read as an educational record,
not a reusable ML framework. Original course instructions and honor-code notes
remain within the lab folders.
