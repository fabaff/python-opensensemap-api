opensensemap-api
================

Python Client for interacting with the `openSenseMap <https://opensensemap.org/>`_
API.

This module is not official, developed, supported or endorsed by
`openSenseMap <https://opensensemap.org/>`_

Installation
------------

The module is available from the `Python Package Index <https://pypi.python.org/pypi>`_.

.. code:: bash

    $ pip3 install opensensemap-api

On a Fedora-based system or a CentOS/RHEL machine with EPEL.

.. code:: bash

    $ sudo dnf -y install python3-opensensemap-api

Usage
-----

The file ``example.py`` contains an example about how to use this module.

Development
-----------

For development is recommended to use a ``venv``.

.. code:: bash

    $ python3 -m venv .
    $ source bin/activate
    $ python3 setup.py develop

License
-------

``opensensemap-api`` is licensed under MIT, for more details check LICENSE.
