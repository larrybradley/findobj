Source Morphological Properties
===============================

.. warning::
    `scikit-image`_ is required for some functionality.

.. _scikit-image: http://scikit-image.org/


`findobj.morphology` provides functions to estimate morphological
properties and the centroid of a source.  The
:func:`~findobj.morphology.data_properties` function calculates the
properties of a single source from a cutout image.  Please see
`~photutils.segmentation.SegmentProperties` for the list of properties
that are calculated.


Centroiding a Source
--------------------

`findobj.morphology` also provides separate functions to calculate
the centroid of a source using three different methods:

    * :func:`~findobj.morphology.centroid_com`: Object center of
      mass determined from 2D image moments.

    * :func:`~findobj.morphology.centroid_1dg`: Fitting 1D Gaussians
      to the marginal x and y distributions of the data.

    * :func:`~findobj.morphology.centroid_2dg`: Fitting a 2D
      Gaussian to the 2D distribution of the data.


Getting Started
---------------


Reference/API
-------------

.. automodapi:: findobj.morphology
    :no-heading:
