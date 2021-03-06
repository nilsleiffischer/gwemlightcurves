.. gwemlightcurves documentation master file, created by
   sphinx-quickstart on Thu Apr 21 14:05:08 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to gwemlightcurves's documentation!
===========================================


Installing gwemlightcurves
--------------------------

The easiest method to install gwemlightcurves is using `pip <https://pip.pypa.io/en/stable/>`_ directly from the `GitHub repository <https://github.com/mcoughlin/gwemlightcurves>`_:

.. code-block:: bash

   $ pip install git+https://github.com/mcoughlin/gwemlightcurves


Table of Contents
-----------------

.. toctree::
   :maxdepth: 3

   examples/index
   examples/lightcurves
   examples/eos

How to run gwemlightcurves
--------------------------

The main product of this package is the command-line executable `run_parameterized_models.py` and `run_parameterized_models_event.py`

To run an analysis:

.. code-block:: bash

   $ run_parameterized_models_event.py --posterior_samples something --name something

For a full list of command-line argument and options, run

.. code-block:: bash

   $ run_parameterized_models_event.py --help

For more details see :ref:`command-line`.

Package documentation
---------------------

Please consult these pages for more details on using gwemlightcurves:

.. toctree::
   :maxdepth: 1

   command-line/index

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
