Sprawozdanie RtD
==================

Header 1
========

Header 2
########

Header 3
--------

Header 4
~~~~~~~~~

Lists
=====

**Bullet list:**

- Point A
- Point B
- Point C
- Point D

**Numbered list**:

#. Point 1
#. Point 2
#. Point 3
#. Point 4

**Definition list**:

term1
    Definition of term1
term2
    Definition of term2

Table
=====

ReST supports multiple ways to make a table.


Simple Table
------------

=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

Grid Table
----------

.. _tbl-grid:

+----------------------+------------+----------+----------+
| Header row, column 1 | Header 2   | Header 3 | Header 4 |
|                      |            |          |          |
+======================+============+==========+==========+
| body row 1, column 1 | column 2   | column 3 | column 4 |
+----------------------+------------+----------+----------+
| body row 2           | ...        | ...      |          |
+----------------------+------------+----------+----------+

Links
=====

External links
--------------

https://www.generic-mapping-tools.org

`GMT Forum <https://forum.generic-mapping-tools.org/>`_

Internal links
--------------

Link to the a module with :doc:`/plot` or :doc:`/plot`.

Link to a section title with `Lists`_.

Link to a target with :ref:`Link to a table <tbl-grid>`.

Link to a GMT parameter :term:`FONT_TITLE`.




Codes
=====

::

    gmt begin map
    gmt basemap -R0/10/0/10 -JX10c/10c -Baf
    gmt end

.. toctree::

  index
  rtd
  contact
