# 10_cpsc330-202_hw09_quarto

The website rendering for homework 5.

## Instructions for Running the Notebook

**There is an environment file associated with this repository.**

1. Load the environment files:

```
conda env create -n analysis_env --file=environment.yml
```

OR (requires `conda lock` to use)

```
conda-lock install -n analysis_env conda-lock.yml
```

2. Activate the environment, then **open the repo from the environment**.

```
conda activate analysis_env
```

then,

```
(analysis_env)# code
```

3. Download the data from [Kaggle](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset). Create a new folder in the root directory called `data`.

4. You are now ready to run the notebook!
