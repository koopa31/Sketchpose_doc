.. _installation:
Installation
=====

First, we advise you to create a conda environment in Python 3.10, in which you will run Napari:

.. code-block:: console

	conda create -n sketchpose_env python=3.10
	conda activate sketchpose_env
	conda install pip
	python -m pip install "napari[all]" --upgrade

Then, Sketchpose can be installed either directly from Napari's plugin manager, or typing:

.. code-block:: console

   pip install napari_sketchpose

