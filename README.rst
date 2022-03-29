========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-mayan-ditch/badge/?style=flat
    :target: https://python-mayan-ditch.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/andreoliwa/python-mayan-ditch/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/andreoliwa/python-mayan-ditch/actions

.. |codecov| image:: https://codecov.io/gh/andreoliwa/python-mayan-ditch/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/andreoliwa/python-mayan-ditch

.. |version| image:: https://img.shields.io/pypi/v/mayan-ditch.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/mayan-ditch

.. |wheel| image:: https://img.shields.io/pypi/wheel/mayan-ditch.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/mayan-ditch

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/mayan-ditch.svg
    :alt: Supported versions
    :target: https://pypi.org/project/mayan-ditch

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/mayan-ditch.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/mayan-ditch

.. |commits-since| image:: https://img.shields.io/github/commits-since/andreoliwa/python-mayan-ditch/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/andreoliwa/python-mayan-ditch/compare/v0.0.0...master



.. end-badges

Dig files from Mayan cabinets

* Free software: MIT license

Installation
============

::

    pip install mayan-ditch

You can also install the in-development version with::

    pip install https://github.com/andreoliwa/python-mayan-ditch/archive/master.zip


Documentation
=============


https://python-mayan-ditch.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
