=====================
 inveniosoftware.org
=====================

.. image:: https://img.shields.io/travis/inveniosoftware/inveniosoftware.org.svg
        :target: https://travis-ci.org/inveniosoftware/inveniosoftware.org

Getting Started
===============

Invenio user documentation uses `Lektor <https://www.getlektor.com>`_, a
powerful static content management system.

Install and running Lektor
--------------------------

To install Lektor, first create a new Python 3 virtualenv:

.. code-block:: console

    $ mkvirtualenv invsite

Next, install Lektor:

.. code-block:: console

    $ (invsite)$ pip install lektor

Launch the web server: go into the root directory of the repository and run
the following command:

.. code-block:: console

    $ lektor server

Visit `localhost:5000 <http://localhost:5000/>`_ in your browser.

About
=====

This repository contains sources of the http://inveniosoftware.org
web site.  Please go there to see the web site in action.
