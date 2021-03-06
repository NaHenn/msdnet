.. Mixed-Scale Dense Network documentation master file, created by
   sphinx-quickstart on Tue Mar  5 12:31:11 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Mixed-Scale Dense Network's documentation!
=====================================================

.. image:: https://anaconda.org/conda-forge/msdnet/badges/version.svg
   :target: https://anaconda.org/conda-forge/msdnet

.. image:: https://anaconda.org/conda-forge/msdnet/badges/latest_release_date.svg
   :target: https://anaconda.org/conda-forge/msdnet

.. image:: https://anaconda.org/conda-forge/msdnet/badges/platforms.svg
   :target: https://anaconda.org/conda-forge/msdnet

.. image:: https://anaconda.org/conda-forge/msdnet/badges/license.svg
   :target: https://anaconda.org/conda-forge/msdnet

.. image:: https://anaconda.org/conda-forge/msdnet/badges/downloads.svg
   :target: https://anaconda.org/conda-forge/msdnet

.. image:: https://travis-ci.com/dmpelt/msdnet.svg?branch=master
   :target: https://travis-ci.com/dmpelt/msdnet

.. image:: https://ci.appveyor.com/api/projects/status/4248fuavnjrhcga2/branch/master?svg=true
   :target: https://ci.appveyor.com/project/dmpelt/msdnet/branch/master


Python implementation of the Mixed-Scale Dense Convolutional Neural Network.

* `[Latest Release] <https://github.com/dmpelt/msdnet/releases/latest>`_
* `[Version history] <https://github.com/dmpelt/msdnet/blob/master/CHANGELOG.md>`_
* `[Bug Tracker] <https://github.com/dmpelt/msdnet/issues>`_
* `[Documentation] <https://dmpelt.github.io/msdnet/>`_

If you use this code in a publication, we would appreciate it if you would refer to:

* Pelt, D. M., & Sethian, J. A. (2018). A mixed-scale dense convolutional neural network for image analysis. Proceedings of the National Academy of Sciences, 115(2), 254-259.

If you use this code to improve tomographic reconstruction, we would appreciate it if you would refer to:

* Pelt, D. M., Batenburg, K. J., & Sethian, J. A. (2018). Improving Tomographic Reconstruction from Limited Data Using Mixed-Scale Dense Convolutional Neural Networks. Journal of Imaging, 4(11), 128.

Development of the Mixed-Scale Dense Convolutional Neural Network method was supported by CAMERA, jointly funded by The Office of Advanced Scientific Research (ASCR) and the Office of Basic Energy Sciences (BES) within the United States Department of Energy's Office of Science. Development of the Python implementation is supported by Centrum Wiskunde & Informatica (CWI), with financial support provided by The Netherlands Organisation for Scientific Research (NWO), project number 016.Veni.192.235.

Installation
-------------

To install this code in a conda environment, run:

.. code-block:: bash


    conda install -c conda-forge msdnet

In other environments, the code can be installed by running:

.. code-block:: bash


    python setup.py install

The code requires the following Python modules: numpy, scipy, tifffile, scikit-image, psutil, h5py, tqdm, numba >=0.41 .
For compiling the code, the scikit-build module is required.

To run on GPU (recommended), a CUDA-capable GPU must be present and CUDA drivers must be installed. In addition, please make
sure that the version of the cudatoolkit package installed by conda matches the CUDA version of your drivers. Specific versions
of cudatoolkit can be installed by running (where 'X.X' is the CUDA version, e.g. '10.0'):

.. code-block:: bash


    conda install cudatoolkit=X.X


Usage
-----

Please see the example scripts for usage information.

.. toctree::
   :maxdepth: 2

   auto_examples/index
   apiref/modules

* :ref:`genindex`
* :ref:`modindex`
