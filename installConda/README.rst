Installing Conda
================

* Run the anaconda installer for Python 3.x from `here <https://www.anaconda.com/distribution/>`_.
* In a new terminal, go to the directory conda was installed into (probably, ``~/anaconda3`` or ``~/opt/anaconda3``) and run
    ``condabin/conda $SHELL``
* In a new terminal, run
    ``conda config --set auto_activate_base false``

This configures your shell and conda such that if you open a new terminal, the environment is as if conda was never installed except that you can type ``conda activate ENV_NAME`` to easily switch to a conda environment.

(More precisely, the above configuration is doing the minimal change to the environment of a new terminal to make ``conda`` visible by adding a directory to ``PATH`` that contains only the ``conda`` command. A new terminal is still picking up the native ``python`` in a new terminal until the user explicitly indicates otherwise with ``conda activate ...``).
