**CAUTION**: The code inside the notebook is fairly crude and scattered. The
notebook in its current state is not meant to be run from top to bottom.
Rather, one must be selective with which parts and in what order to run
the blocks. There is currently no intention of further documentation.

# Setup

Easiest way to setup is to use a python environment and package manager.
Although you may use pip/venv, conda kind of does both so it's easier.
Simply run these commands after installing conda:

```
conda create -n cs456env
conda activate cs456env
conda install -c conda-forge tensorflow
conda install -c conda-forge keras
conda install jupyter
```

Furthermore, there are several other dependencies, listed inside the actual
notebook as they come into play. Here is an incomplete extract:

- personachat conversation data: http://parl.ai/downloads/personachat/personachat.tgz
- scikit-learn: `conda install scikit-learn`


# Use

To run, start jupyter in a root working directory

```
cd <path_to_working_tree> && jupyter notebook
```

and open up the notebook.

