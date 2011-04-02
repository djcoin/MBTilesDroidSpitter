Overview
========

Read an `SQLite' database <http://www.sqlite.org/>`_ formatted as `MBtiles file format <http://mapbox.com/documentation/mbtiles-file-format>`_.

See https://github.com/djcoin/MBTilesDroidSpitterExampleSimple for an example of use and how to make your *SQLite database Android compatible*.

Features
--------

- Load the database using a full path
- Load a tile given its x, y, z parameter as a Bitmap or Drawable (return null if no tile found)
- Load metadata of the table given it's version number. Ensure failure if the given metadata table does not respect the spec

Contributors
============

- Simon Thépot aka djcoin <simon.thepot@gmail.com> <simon.thepot@makina-corpus.com>. Work done while being at `Makina Corpus <http://www.makina-corpus.com>`_
