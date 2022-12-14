Usage
=====

Crowdliness is autodiadictism raised recursively to a convoluted power.
-----------------------------------_-----------------------------------

The GNNgraph is approach convoluted and recursive in nature; it involves several steps ... the most important step might be the fourth step of using documentation to add/attract collaborators ... but all steps are about collaboration:

1) At first, we collect, curate, play with, annotate a forkable repository of sharabel neural network machine learning models -- we focus more on a particular kind of machine learning models, graph neural networks, but the foundation of this repository is the Git-based workflow for a version-controlled repository of tutorials.
2) Then, we present that portfolio of tutorial models or body of GNN knowledge as an interconnected knowledge GRAPH ... we might use the Git digraph to draw some linkages. The point of this second step is to graphically display connections, trees, comparabilities, differences, similarities, hybridizations ... as we attempt to do the analytics on this graph, insights will emerge. Most insights will be unexpected, but we should, at minimium, expect that the holes or gaps in our knowledge become apparent.
3) As we perform knowledge graph analytics, we will find ways to improve our continuous integration and continuous deployment processes in the data API or other aspects of constructing tools for doing the analytics on these nueral network learning models.
4) Finally, deploying and improving the documentation flow, as in ReadTheDocs.io, is an important part of this ... actually the process from the start should be thought of as a sharable development project in which the goal is to add collaborators.

The GNNgraph way is entirely about being aware of where the crowd in machine learning is going and imitating the very examples ... it's much like cooking except that since we learn through errors, we can just delete our errors or make revisions and improve ... so what, if we don't get it right, at first -- the point is to learn. Ultimately, as skill levels improve ... 

At first, we learn superficially by learning how others have learned, but then we learn deeply by teaching others or sharing our process for what we have learned.

.. _installation:

Installation
------------

To use GNNgraph, you will first install it using pip:

.. code-block:: console

   (.venv) $ pip install gnngraph
 
 
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

