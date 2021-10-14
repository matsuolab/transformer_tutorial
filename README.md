## PyTorch Transformer Tutorial

A refactoring example of the standard PyTorch transformer language translation tutorial.

Initial code available [here](https://github.com/pytorch/tutorials/blob/master/beginner_source/transformer_tutorial.py).

### Installation

```shell
# Modify as needed the environment.yml (like the name or prefix)

# Create a conda environment
$ conda env create -f environment.yml
$ conda activate tt

# Download the trained spacy pipelines
$ (tt) python -m spacy download en_core_web_sm
$ (tt) python -m spacy download de_core_news_sm
```

### Running

```shell
$ conda activate tt
$ (tt) python main.py
```