# scipy-2023-tutorial

Tutorial materials for SciPy 2023


# Installation Instructions

Clone this repository to get the tutorial materials:

```
git clone https://github.com/sympy/scipy-2023-tutorial.git
```

The SymPy tutorial requires Python 3.9 or greater (3.11 is recommended). There
is a file `requirements.txt` in this repository that lists all the
dependencies that need to be installed to run the tutorial materials. You can
install the dependencies with conda

```py
conda env create --file environment.yml
conda activate sympy-tutorial
```

or pip

```
pip install -r requirements.txt
```

Importantly, make sure you have the *latest* version of SymPy (1.12), and are
able to run Jupyter notebooks. The requirements file additionally includes
some optional dependencies which are used in some parts of the tutorial such
as `numpy` and `matplotlib`. These dependencies are not used for the majority
of the tutorial but if you do not have them you may not be able to complete
some of the later sections.

To start the tutorial, run `jupyter lab` (or `jupyter notebook`), and start
with `tutorials/00-Index.ipynb`.
