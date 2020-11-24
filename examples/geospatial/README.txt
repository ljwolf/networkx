Geospatial
----------

The following geospatial examples showcase different ways of performing
network analyses using packages within the geospatial Python ecosystem.
Example spatial files are stored directly in this directory.

Dependencies
~~~~~~~~~~~~

`GeoPandas <https://geopandas.readthedocs.io/>`__ provides
interoperability between geospatial formats and storage mechanisms
(e.g., databases) and Pandas data frames for tabular-oriented processing
of spatial data, as well as a wide array of supporting functionality
including spatial indices, spatial predicates (e.g., test if geometries
intersect each other), spatial operations (e.g., the area of overlap
between intersecting polygons), and more.

`PySAL <https://pysal.org/>`__ provides a rich suite of spatial analysis
algorithms. From a network analysis context, `spatial
weights <https://pysal.org/libpysal/api.html#spatial-weights>`__
provide… (Levi please add more here).

See the following examples that use PySAL:

* ``examples/geospatial/plot_delaunay.py``
* ... (depends on split between PySAL and Momepy examples)

`momepy <http://docs.momepy.org/en/stable/>`__ builds on top of
GeoPandas and PySAL to provide a suite of algorithms focused on urban
morphology. From a network analysis context, momepy enables you to
convert your line geometry to ``networkX.MultiGraph`` and back to 
``GeoDataFrames`` and apply a range of analytical functions aiming at 
morphological description of (street) network configurations.

See the following examples that use momepy:

* ...

Key Concepts
~~~~~~~~~~~~

One of the essential tasks in network analysis of geospatial data is
defining the spatial relationships between spatial features (points,
lines, or polygons).

``PySAL`` provides several ways of representing these spatial
relationships between features using the concept of spatial weights.
These include relationships such as ``Queen``, ``Rook``, ...
(Levi please add more here with a brief explanation of each).

(Martin please add a brief intro to abstractions used in your examples)
