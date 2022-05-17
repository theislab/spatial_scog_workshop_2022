# eggplant

This sub directory contains the files necessary to run the `eggplant` tutorial.
There's a single notebook `2022-05-24-scog.ipynb` (found in the folder
`notebooks`) that outlines the analysis of two different data sets: (i) the
developmental heart and (ii) the mouse brain (with different perturbations).

The aforementioned notebook also contains code that will (hopefully)
automatically download the data for you, the data files are ~900MB in size, so
it might be a good idea to download this prior to the session, however it
usually only takes a few minutes for the download to complete on a decent
network. If the automatic download fails, there are also instructions for a
manual download in the notebook.

To run this `eggplant` tutorial, we recommend that you use the _associated
conda_ environment provided by the instructors (also found in the `conda`
folder). To create a conda environment from a `yml` file use the command: `conda
env create --file path_to_yml_file`. The conda environment created by the yaml
file that we provide will be named `scog-eggplant`.

`eggplant` supports both GPU and CPU usage, but the analysis is _much_ faster
using a GPU, so if you have access to both - there's a strong preference for the
GPU. However, **pre-analyzed** data is also provided, allowing you to skip the
computationally heavy steps, while still being able to work through the notebook.

