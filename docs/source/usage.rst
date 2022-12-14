Usage
=====

.. _installation:

Installation
------------

To use GNNgraph, you will first install it using pip:

.. code-block:: console

   (.venv) $ pip install gnngraph

Creative cooking by abusing recipes
-----------------------------------

GNNgraph builds upon a curated repository of graph-related tutorials as ingredients for your own recipe of a tutorial. At first, we learn superficially by learning how others have learned, but then we learn deeply by teaching others or sharing our process for what we have learned. Crowdliness is autodiadictism raised to a higher power.
 
you can use the ``gnngraph.get_random_ingredients()`` function:

.. autofunction:: gnngraph.get_random_ingredients

The ``kind`` parameter should be either ``"rnn"``, ``"pytorch"``,
or ``"gradient"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import gnngraph
>>> gnngraph.get_random_ingredients()
['shell', 'awk', 'sed']

