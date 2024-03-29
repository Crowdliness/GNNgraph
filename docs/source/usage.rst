Usage
=====

Crowdliness
-----------

Crowdliness is autodiadictism raised recursively to a convoluted power ... it's like BurningMan, except maybe a more naive, more primeval, but a highly participatory proto-BurningMan that didn't even have a location yet, before BurningMan primarily attracted reporters, spectators and gawkers. Crowdliness is that thing which is so raw and nakedly intriguing that it might attract a crowd.

GNNgraph illustrates how crowdly autodidactism is convoluted and recursive in nature. GNNgraph is mathy, but less like a classroom and more like jazz or improvisational abstract art in that it is fundamentally autodidactic in nature. Playing well in a sandbox involves a LOT of experimentation and practice alone ... but, at some point or when skills get to a certain level, it is transitions into something, like BurningMan Project was around 1985 or early 1986, that is fundamentally about attracting people interested in collaborative jamming.

GNN graph involves several general steps ... of course, these steps are entirely mallable ... but a basic outline illustrates the gist. We believe that the most important step might be the fourth step of developing explanatory documentation to add/attract autodidactive collaborators ... but each of these steps must necessarily be about ultimately stimulating collaboration.

1) At first, we collect, curate, play with, annotate a forkable repository of sharabel neural network machine learning models -- we focus more on a particular kind of machine learning models, graph neural networks, but the foundation of this repository is the Git-based workflow for a version-controlled repository of tutorials.

2) Then, we present that portfolio of tutorial models or body of GNN knowledge as an interconnected knowledge GRAPH ... we might use the Git digraph to draw some linkages. The point of this second step is to graphically display connections, trees, comparabilities, differences, similarities, hybridizations ... as we attempt to do the analytics on this graph, insights will emerge. Most insights will be unexpected, but we should, at minimium, expect that the holes or gaps in our knowledge become apparent.

3) As we perform knowledge graph analytics, we will find ways to improve our continuous integration and continuous deployment processes in the data API or other aspects of constructing tools for doing the analytics on these nueral network learning models.

4) Finally, deploying and improving the documentation flow, as in https://Sphinx.ReadTheDocs.io or ReadTheDocs.io, is an important part of this ... actually the process from the start should be thought of as a sharable development project in which the goal is to add collaborators.

The GNNgraph way is entirely about being shrewdly aware of where the crowd in machine learning is going and imitating the very most interesting examples ... it's much like cooking we learn through errors in the preparation process, except this is easier in that we can just delete our errors or, with version control, retrace our steps, make revisions to build upon what did work and generally try wilder things to improve ... so what, if we don't get it right, at first -- the point is to experiment and learn. Ultimately, as the rising tide of skill levels lifts all boats. 

At first, we learn superficially by learning how others have learned, but then we learn more deeply by teaching others, collaborating, debating ideas and generally sharing the open source of our entire process as we learn and extend our skill levels.

.. _installation:

Installation
------------

To use GNNgraph, you will first install it using pip:

.. code-block:: console

   (.venv) $ pip install gnngraph
 
 
you can use the ``gnngraph.get_random_ingredients()`` function:

.. autofunction:: gnngraph.get_random_ingredients

The ``kind`` parameter should be either ``"rnn"``, ``"pytorch"``,
or ``"gradient"``. Otherwise, :py:func:`gnngraph.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import gnngraph
>>> gnngraph.get_random_ingredients()
['shell', 'awk', 'sed']

