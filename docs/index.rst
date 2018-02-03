.. SciDB-Py documentation master file, created by
   sphinx-quickstart on Sat Jun 17 10:14:34 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

SciDB-Py Documentation
======================

.. warning::

    Since SciDB-Py Release **16.9.1** (released in `September 2017`)
    the library has been rewritten entirely from scratch. ``16.9.1``
    and newer versions are **not compatible** with the previous
    versions of the library. The documentation for the previous
    versions is available at `SciDB-Py documentation (legacy)
    <http://scidb-py.readthedocs.io/en/v16.9-legacy/>`_. GitHub pull
    requests are still accepted for the previous versions, but the
    code is not actively maintained.

.. toctree::
   :maxdepth: 4

   guide
   api

Version Information
-------------------

The major and minor version numbers of SciDB-Py track the major and
minor version of SciDB they are compatible with. For example SciDB-Py
``16.9.1``, ``16.9.2`` or ``16.9.10`` are all compatible with SciDB
``16.9.x``.

During SciDB ``16.9``, Shim (HTTP service for SciDB) transitioned from
query authentication to session authentication. SciDB-Py has been
updated to be compatible with the new Shim. Below is the compatibility
matrix between SciDB-Py and Shim:

=====       =====
SciDB-Py    Shim
=====       =====
``16.9.1``  query authentication (old Shim)
``16.9.2``  query authentication (old Shim)
``16.9.10`` session authentication (new Shim)
=====       =====

From ``16.9.10`` onwards only Shim with session authentication is
supported.

Indices and Tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
