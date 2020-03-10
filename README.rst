Conda environments with SnapPy
==============================

This repository contains files to create a conda environment containing
`SnapPy <https://snappy.math.uic.edu/>`_ (and `SageMath <http://www.sagemath.org/>`_).

To create and activate an environment, download `snappy-2.7.yml <https://raw.githubusercontent.com/unhyperbolic/condaForSnapPy/master/snappy-2.7.yml>`_ (without SageMath) or `snappy-2.7-sage-8.9.yml <https://raw.githubusercontent.com/unhyperbolic/condaForSnapPy/master/snappy-2.7-sage-8.9.yml>`_ (with SnapPy, Mac and Linux only), go to the directory with the file and type::

    conda env create -f FILE.yml --name PICK_AN_ENV_NAME
    conda activate PICK_AN_ENV_NAME

Instructions how to install conda are `here <installConda/>`_. More details are in the `conda documentation <https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html>`_.
