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

**WARNING**:

For Windows users, CUDA version of PyTorch may not be installed properly. When the plugin starts for the first time, it checks whether
CUDA version is installed. If not, it tries to install it using light-the-torch library. If this does not work, you should re-install
CUDA torch and torchvision versions manually, otherwise the plugin will not work properly.

