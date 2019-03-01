# Machine Learning Notebooks

Repository for SMU's Machine Learning in Python (CSE 5324/7324) assignments

Group:

1. Jake Oien
2. Seungki Lee
3. Jenn Le

## Set Up Your Conda Environment

In the root level folder, run the command

```
conda env create -f environment.yml
```

To activate the environment, run

```
source activate mlenv
```

If you are getting a `NameError: name 'compose' is not defined` error, run the following

```
pip install --upgrade pip
pip uninstall cytoolz
pip install cytoolz
conda update cytoolz
```
