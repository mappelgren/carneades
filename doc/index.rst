The Carneades model of argumentation
====================================

This is a Python implementation of the `Carneades argumentation model
<http://carneades.github.io/carneades/Carneades/>`_. It closely
follows the Haskell `Carneades DSL
<http://www.cs.nott.ac.uk/~bmv/CarneadesDSL>`_ by Bas van Gijzel and
Henrik Nilsson, especially `this detailed code <http://www.cs.nott.ac.uk/~bmv/Code/CarneadesDSLWithCycleChecking.lhs>`_.

The main module ``caes.py`` uses the ``igraph`` package for
representing dependencies between arguments. For documentation, see

* `igraph tutorial <http://igraph.org/python/doc/tutorial/>`_
* `igraph manual and API
  <http://igraph.org/python/doc/igraph-module.html>`_

Plotting in ``igraph`` is dependent on the ``pycairo`` library which provides Python
bindings to the `Cairo library <http://www.cairographics.org>`_, as
illustrated below.

.. image:: argset.png
   :width: 500 px

Contents
--------

.. toctree::
   :maxdepth: 1
  
   CAES API <api/index>
   


Indices and tables
==================

* :ref:`genindex`
* :ref:`search`

