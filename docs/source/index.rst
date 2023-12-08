Welcome to Sketchpose's documentation!
===================================

`Sketchpose <https://www.napari-hub.org/plugins/napari-sketchpose>`_ is a Napari plugin developed in Python, dedicated to
cells and bacteria segmentation.

The CNN is based on `Cellpose <https://www.cellpose.org/>`_ architecture, but works for very sparse annotations. Its main advantage is that it allows
frugal annotation, in the sense that you can annotate only pieces of cells and backgrounds, as well as their borders.

Our method can be primarily used in two ways: either through the Napari plugin, or directly via command line if you
already have your dataset partially or completely annotated. The advantage of the plugin is that it allows for
interactive work, which means you can observe the progress of training and add annotations on the fly.

You can learn more about our method reading the `related paper <https://hal.science/hal-04330824>`_.

First check out the :doc:`installation` section to know how to install it.

If you use this plugin, please cite the paper:

Clément Cazorla, Nathanaël Munier, Renaud Morin, Pierre Weiss. Sketchpose: Learning to Segment
Cells with Partial Annotations. 2023. ffhal-04330824f

.. code-block:: bibtex

    @unpublished{cazorla:hal-04330824,
      TITLE = {{Sketchpose: Learning to Segment Cells with Partial Annotations}},
      AUTHOR = {Cazorla, Cl{\'e}ment and Munier, Nathana{\"e}l and Morin, Renaud and Weiss, Pierre},
      URL = {https://hal.science/hal-04330824},
      NOTE = {working paper or preprint},
      YEAR = {2023},
      MONTH = Dec,
      KEYWORDS = {Cellpose -Segmentation -Frugal learning -Napari -Deep learning -Distance map},
      PDF = {https://hal.science/hal-04330824/file/sketchpose_hal.pdf},
      HAL_ID = {hal-04330824},
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