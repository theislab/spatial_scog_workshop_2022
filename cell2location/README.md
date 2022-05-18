# cell2location

This notebook can be openned in Google Colab [![in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BayraktarLab/cell2location/blob/master/docs/notebooks/cell2location_tutorial.ipynb). When in Colab simply follow code cells - not additional installation is needed.

For running this tutorial on your system you need to install cell2location in your conda environment with `pip install git+https://github.com/BayraktarLab/cell2location.git#egg=cell2location[tutorials]`. If you encounter any issues we suggest creating a separate conda environment for installing cell2location as shown below.

Create conda environment and install `cell2location` package

```bash
conda create -y -n cell2loc_env python=3.9

conda activate cell2loc_env
pip install git+https://github.com/BayraktarLab/cell2location.git#egg=cell2location[tutorials]
```

Finally, to use this environment in jupyter notebook, add jupyter kernel for this environment:

```bash
conda activate cell2loc_env
python -m ipykernel install --user --name=cell2loc_env --display-name='Environment (cell2loc_env)'
```

If you do not have conda please install Miniconda first:

```bash
cd /path/to/software
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh
# use prefix /path/to/software/miniconda3
```

Before installing cell2location and it's dependencies, it could be necessary to make sure that you are creating a fully isolated conda environment by telling python to NOT use user site for installing packages by running this line before creating conda environment and every time before activatin conda environment in a new terminal session:

```bash
export PYTHONNOUSERSITE="literallyanyletters"
```
