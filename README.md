# Setup

Easiest way to setup is to use a python environment and package manager.
Although you may use pip/venv, conda kind of does both. Run these commands:

```
conda create -n cs456env
conda activate cs456env
conda install -c conda-forge tensorflow
conda install -c conda-forge keras
conda install jupyter
```

# Use

To run, start jupyter in a root working directory

```
cd <path_to_working_tree> && jupyter notebook
```

