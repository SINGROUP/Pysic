.. file:coremirror class

.. _coremirror class:



.. file:coremirror class - description

.. _coremirror class - description:



.. module:: pysic.core

================
CoreMirror class
================

CoreMirror is a Python representation of the Fortran core.
When running pysic, it is intended that a single instance
of CoreMirror exists, created automatically when importing
:mod:`~pysic` as the :data:`~pysic.calculator.Pysic.core` object in
:class:`~pysic.calculator.Pysic`.

Whenever changes are made in the Fortran core, they should
also be reflected in the CoreMirror. This way one has always
easy access to the state of the Fortran core without having
to directly access the core and parse the data.

Normally, the user should not touch the CoreMirror directly.
It is automatically handled through :class:`~pysic.calculator.Pysic`.

.. file:coremirror class - autogenerated

.. _coremirror class - autogenerated:



List of Methods
---------------

- :meth:`~pysic.core.CoreMirror.atoms_ready` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.cell_ready` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.charges_ready` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.coulomb_summation_ready` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.get_atoms` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.neighbor_lists_ready` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.potentials_ready` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.set_atomic_momenta` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.set_atomic_positions` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.set_atoms` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.set_cell` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.set_charges` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.set_coulomb` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.set_neighbor_lists` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.set_potentials` (meant for internal use)
- :meth:`~pysic.core.CoreMirror.view_fortran` (for testing)

Full documentation of the CoreMirror class
------------------------------------------

.. currentmodule:: pysic.core
.. autoclass:: CoreMirror
   :members:
   :undoc-members:

