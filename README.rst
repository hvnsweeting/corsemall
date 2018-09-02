corsemall - serve JSON CORS for local JS dev
============================================

corsemall - CORS 'em all

.. image:: https://travis-ci.org/hvnsweeting/corsemall.svg?branch=master
    :target: https://travis-ci.org/hvnsweeting/corsemall

For developing JavaScript applications, which get data from backend. There are
circustances that backend not available, or on a remote has not allow CORS
(yet), or the network is just too slow.
This helps bypass these problems by saving the data once to local '.json' files
(manually) then serves them from local.

Installation
------------

By using pip::

    pip install corsemall

Usage
-----

To serve JSON files at path with CORS allowed for all, run::

  corsemall PATH_TO_DIRECTORY_CONTAINS_JSON_FILE

Features
--------

- Supports both Python2 and Python3
- Run on Linux, OSX, Windows

Authors
-------

Viet Hung Nguyen <hvn@familug.org>
