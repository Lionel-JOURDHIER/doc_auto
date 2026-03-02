.. My_first_autodoc documentation master file, created by
   sphinx-quickstart on Mon Mar  2 11:39:45 2026.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

My_first_autodoc documentation
==============================

Add your content using ``reStructuredText`` syntax. See the
`reStructuredText <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_
documentation for details.

.. include:: ../../README.md
   :parser: myst_parser.sphinx_

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   self
   mon_api

Modules
===================

Outils Mathématiques
--------------------

.. automodule:: app.modules.my_math
   :members:
   :undoc-members:
   :show-inheritance:

Logique métier
--------------

.. automodule:: app.modules.modules
   :members:
   :undoc-members:
   :show-inheritance:
