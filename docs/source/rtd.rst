Sprawozdanie RtD
==================

Header 1
########

Header 2
--------

Header 3
~~~~~~~~~

Header 4
"""""""""

Listy
######

**Lista myślników:**

- Point A
- Point B
- Point C
- Point D

**Lista numerowana**:

#. Point 1
#. Point 2
#. Point 3
#. Point 4

**Lista definicji**:

term1
    Definicja term1
term2
    Definicja term2

Tabela
######

ReST wiele opcji tworzenia tabel

Prosta Tabla
------------

=====  =====  =======
A      B      A i B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

Grid Tabela
-----------

.. _tbl-grid:

+----------------------+------------+----------+----------+
| Header row, column 1 | Header 2   | Header 3 | Header 4 |
|                      |            |          |          |
+======================+============+==========+==========+
| body row 1, column 1 | column 2   | column 3 | column 4 |
+----------------------+------------+----------+----------+
| body row 2           | ...        | ...      |          |
+----------------------+------------+----------+----------+

Linki
######

Zewnętrzne Linki
--------------

https://www.generic-mapping-tools.org

`GMT Forum <https://forum.generic-mapping-tools.org/>`_

Wewnętrzne Linki
--------------

Link do modułu: :doc:`/plot`.

Link do tytułu sekcji `Lists`_.

Link do znacznika (targetu) za pomocą :ref:`Link do tabeli <tbl-grid>`.

Link do parametru GMT :term:`FONT_TITLE`.

Kody
#####

.. code-block:: bash

    gmt begin map
    gmt basemap -R0/10/0/10 -JX10c/10c -Baf
    gmt end


``echo "Hello, World!"``

Notatki Informacyjne
######################

.. note::
    Notatka informacyjna - typ note

.. tip::
    Notatka informacyjna - typ tip


Zdjęcie
#######

.. figure:: https://about.readthedocs.com/images/logo-opengraph.png
   :width: 90%
   :alt: Read The Docs - logo

   Zdjęcie read the docs logo
