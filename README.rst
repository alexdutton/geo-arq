Ideas and thoughts for the provision of geospatial capabilities in ARQ
======================================================================

Overview
--------

TODO


Status of this document
-----------------------

This document is intended to gather information from around the web as the
basis for constructive discussion.


Use cases
---------

Hereafter, 𝑑 is a distance, 𝑥 is a point, and 𝑝 is a simple polygon.

 * "Find me things near 𝑥"
 * "Find everything within 𝑑m of 𝑥"
 * "Find all points contained within 𝑝"
 * "Find all geometries contained within 𝑝"


Existing implementations
------------------------

Parliament
~~~~~~~~~~

`Parliament <http://parliament.semwebcentral.org/>`_ is a triple store built on
top of Jena and Sesame.

GeoSpatialWeb
~~~~~~~~~~~~~



GeoARQ
~~~~~~

To quote the README, `GeoARQ <https://github.com/castagna/GeoARQ>`_ "uses
Lucene Spatial via an ARQ property function to allow to search nearby a
location. All the RDF instances which use the WGS84 geo positioning RDF
vocabulary [1] to represent geographic coordinates are indexed.

"This is experimental (and unsupported)."
