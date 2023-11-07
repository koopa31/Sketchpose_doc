Welcome to Sketchpose's documentation!
===================================

`Sketchpose <https://www.napari-hub.org/plugins/napari-sketchpose>`_ is a Napari plugin developed in Python, dedicated to
cells and bacteria segmentation.

The CNN is based on `Cellpose <https://www.cellpose.org/>`_ architecture, but works for very sparse annotations. Its main advantage is that it allows
frugal annotation, in the sense that you can annotate only pieces of cells and backgrounds, as well as their borders.

Our method can be primarily used in two ways: either through the Napari plugin, or directly via command line if you
already have your dataset partially or completely annotated. The advantage of the plugin is that it allows for
interactive work, which means you can observe the progress of training and add annotations on the fly.

You can learn more about our method reading the `related paper <https://hal.inria.fr/hal-03927879>`_.

First check out the :doc:`installation` section to know how to install it.

If you use this plugin, please cite the paper:

Cazorla, C., Munier, N., Weiss, P., & Morin, R. (2023). Sketchpose: Scaling Down Cellpose from Massive to Sparse
Data.

.. code-block:: bibtex

    @unpublished{weiss:hal-03927879,
      TITLE = {{Sketchpose: Scaling Down Cellpose from Massive to Sparse Data}},
      AUTHOR = {Weiss, Pierre and Cazorla, Cl{\'e}ment and Morin, Renaud},
      URL = {https://hal.inria.fr/hal-03927879},
      NOTE = {working paper or preprint},
      YEAR = {2023},
      MONTH = Jan,
      PDF = {https://hal.inria.fr/hal-03927879/file/main_nature.pdf},
      HAL_ID = {hal-03927879},
      HAL_VERSION = {v1},
    }


.. note::

   This project is still under active development. We welcome any suggestions for improvement from users.
    Thank you

.. figure:: https://bitbucket.org/koopa31/napari-sketchpose/raw/b691817e9e20a3c1c2bc69277579f6fb9b26354e/images/frugalpose.gif
   :alt: GIF Image

    Image Credit: Eduard Muzhevskyi
Contents
--------

.. toctree::
   installation
   usage