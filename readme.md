# SentimentScope: IMDB sentiment analysis

## Project overview
This repository contains a notebook-based sentiment-analysis project for the IMDB movie-review dataset. The work focuses on a binary sentiment-classification task: determine whether a review is positive or negative.

## What is implemented
The notebook is a practical NLP workflow with the following structure:
- load the dataset from the `aclImdb` folder
- prepare positive and negative review text
- convert text into model-ready features
- train and validate a machine-learning classifier
- evaluate performance and inspect the results

The notebook also introduces a transformer-based approach in the later project description, which indicates the project is instructional and exploratory rather than a finalized production model.

## Repository state
This repository does not currently include a complete dependency file at the root. It also expects the IMDB dataset to be present locally before the notebook can run.

## Required data
The notebook expects the dataset in a folder such as:
```bash
aclImdb/
```
with subfolders for train/test and positive/negative reviews.

If the dataset is not present locally, the notebook cannot be executed end-to-end.

## Install and run
```bash
pip install -r requirements.txt
jupyter notebook
```
Then open `SentimentScope_starter.ipynb` and run the cells in order.

## Dependencies
The notebook uses common Python data-science packages, including:
- pandas
- numpy
- matplotlib
- scikit-learn
- jupyter
- PyTorch
- transformers

## Results and caveats
The repository does not currently include committed evaluation output or a verified model artifact. Because of that, the safe description is that the notebook implements a sentiment-classification pipeline and expects the IMDB dataset in the local environment.

## Tools used
- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- PyTorch / transformer-based modeling workflow

## Attribution
This project is a learning and experimentation repository for NLP sentiment analysis, not a production service or a published model benchmark.
