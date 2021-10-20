***********************************************************************
fortnet-ase: Interfacing Fortnet with the Atomic Simulation Environment
***********************************************************************

|license|
|latest version|
|doi|
|issues|

fortnet-ase provides an interface between the neural network implementation
`Fortnet <https://github.com/vanderhe/fortnet>`_ and the Atomic Simulation
Environment (`ASE <https://wiki.fysik.dtu.dk/ase/>`_). The calculator employs
Fortnet as a prediction engine for the total energy of a system as well as the
calculation of atomic forces, e.g. for geometry optimizations and molecular
dynamics.

|logo|

Installation
============

|build status|

The package can be installed via conda-forge::

  conda install fortnet-ase

Alternatively, the package can be downloaded and installed via pip into the
active Python interpreter (preferably using a virtual python environment) by ::

  pip install fortnet-ase

or into the user space issueing ::

  pip install --user fortnet-ase

Documentation
=============

|docs status|

Consult following resources for documentation:

* `Step-by-step instructions with selected examples (Fortnet-Ase Recipes)
  <https://fortnet-ase.readthedocs.io/>`_

Contributing
============

New features, bug fixes, documentation, tutorial examples and code testing is
welcome during the ongoing fortnet-ase development!

The project is `hosted on github <https://github.com/vanderhe/fortnet-ase/>`_.
Please check `CONTRIBUTING.rst <CONTRIBUTING.rst>`_ for guide lines.

I am looking forward to your pull request!

License
=======

fortnet-ase is released under the BSD 2-clause license. See the included
`LICENSE <LICENSE>`_ file for the detailed licensing conditions.

.. |logo| image:: ./utils/art/logo.svg
    :alt: Fortnet logo
    :width: 90
    :target: https://github.com/vanderhe/fortnet/

.. |license| image:: https://img.shields.io/github/license/vanderhe/fortnet-ase
    :alt: BSD-2-Clause
    :scale: 100%
    :target: https://opensource.org/licenses/BSD-2-Clause

.. |latest version| image:: https://img.shields.io/github/v/release/vanderhe/fortnet-ase
    :target: https://github.com/vanderhe/fortnet-ase/releases/latest

.. |doi| image:: https://zenodo.org/badge/356394988.svg
   :target: https://zenodo.org/badge/latestdoi/356394988

.. |docs status| image:: https://readthedocs.org/projects/fortnet-ase/badge/?version=latest
    :alt: Documentation Status
    :scale: 100%
    :target: https://fortnet-ase.readthedocs.io/en/latest/

.. |issues| image:: https://img.shields.io/github/issues/vanderhe/fortnet-ase.svg
    :target: https://github.com/vanderhe/fortnet-ase/issues/

.. |build status| image:: https://img.shields.io/github/workflow/status/vanderhe/fortnet-ase/CI
    :target: https://github.com/vanderhe/fortnet-ase/actions/
