# Python tutorials for OpenMM

This guide is a set of [Jupyter notebooks](http://jupyter.readthedocs.io/) that will help you get up and running quickly with OpenMM and Python.

## Getting started

We recommend you use [`miniconda`](https://conda.io/miniconda.html) and the [`conda`](https://conda.io) package manager.
If you don't already have `miniconda` installed, you can easily install it from the terminal:
```bash
# For Mac OS X, substitute `MacOSX` for `Linux` below
wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash -b ./Miniconda3-latest-Linux-x86_64.sh -p $HOME/miniconda
export PATH=$HOME/miniconda/bin:$PATH
```
Install the dependencies with `conda`:
```bash
conda install --yes -c omnia -c conda-forge jupyter notebook openmm mdtraj nglview
```

## Tutorials

* 01 - [Creating and importing molecular systems in OpenMM](https://github.com/choderalab/openmm-tutorials/blob/master/01%20-%20Creating%20and%20importing%20molecular%20systems%20in%20OpenMM.ipynb)
* 02 - [Integrators and sampling](https://github.com/choderalab/openmm-tutorials/blob/master/02%20-%20Integrators%20and%20sampling.ipynb)

## More resources

Be sure to check out the OpenMM Documentation site http://docs.openmm.org, which contains an excellent [User Guide](http://docs.openmm.org/7.1.0/userguide/index.html), [Python API reference](http://docs.openmm.org/7.1.0/api-python/index.html), and [more tutorials](http://openmm.org/tutorials/index.html).
