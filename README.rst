======================
Cookiecutter PyPackage
======================

Cookiecutter_ template for a Python package.

* GitHub repo (source this repo was forked from): https://github.com/audreyfeldroy/cookiecutter-pypackage/
* Documentation: https://cookiecutter-pypackage.readthedocs.io/
* Free software: BSD license

Features
--------

(Note: modified from original for artefactual-labs use)

* Testing setup with ``pytest``
* GitHub Actions: Ready for Github Actions test CI
* ``tox`` testing: Setup to easily test for Python 3.6, 3.7, 3.8, 3.9
* Makefile to assist with building packages and publishing to PyPI
* Command line interface using ``Click``
* ``pre-commit`` config with rules for ``flake8`` and ``Black``

.. _Cookiecutter: https://github.com/cookiecutter/cookiecutter

Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/artefactual-labs/cookiecutter-pypackage.git

Then:

* Create a repo and put it there
* Install pre-commit
* Add your code and tests
* Add your package requirements to ``requirements/base.txt``
* Release your package on PyPI using the provided Makefile

For more details, see the `cookiecutter-pypackage tutorial`_.

.. _`cookiecutter-pypackage tutorial`: https://cookiecutter-pypackage.readthedocs.io/en/latest/tutorial.html
