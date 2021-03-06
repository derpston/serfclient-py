serfclient
==========

The Python interface to Serf, the decentralised solution for
service discovery and orchestration.

.. image:: https://secure.travis-ci.org/KushalP/serfclient-py.png?branch=master
    :alt: Travis-CI badge
    :target: http://travis-ci.org/KushalP/serfclient-py
.. image:: https://gemnasium.com/KushalP/serfclient-py.png
    :alt: Gemnasium badge
    :target: https://gemnasium.com/KushalP/serfclient-py
.. image:: https://pypip.in/v/serfclient/badge.png
    :alt: PyPI latest version badge
    :target: https://pypi.python.org/pypi/serfclient
.. image:: https://coveralls.io/repos/KushalP/serfclient-py/badge.png?branch=master
    :alt: Code coverage badge
    :target: https://coveralls.io/r/KushalP/serfclient-py?branch=master

Installation
------------

serfclient requires a running Serf agent. See `Serf's agent documentation
<http://www.serfdom.io/docs/agent/basics.html>`_ for instructions.

To install serfclient, simply:

.. code-block:: bash

    $ sudo pip install serfclient

or alternatively (you really should be using pip though):

.. code-block:: bash

    $ sudo easy_install serfclient

or from source:

.. code-block:: bash

    $ sudo python setup.py install

Getting Started
---------------

.. code-block:: python

    from serfclient.client import SerfClient

    client = SerfClient()
    client.event('foo', 'bar')

Development
------------

serfclient requires a running Serf agent. See `Serf's agent documentation
<http://www.serfdom.io/docs/agent/basics.html>`_ for instructions.

To run the tests, simply:

.. code-block:: bash

    $ python setup.py test
