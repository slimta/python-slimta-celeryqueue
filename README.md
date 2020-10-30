#### [Project Homepage][1]
#### [API Documentation][2] and [Manual][3]

--------------------

#### _This extension is no longer maintained._

About
=====

Adds a [Celery][4] based queue extension to python-slimta. This queue is
intended to replace the built-in queuing mechanisms and allows for a more
distributed model of reception, storage and delivery.

[![Build Status](https://travis-ci.org/slimta/python-slimta-celeryqueue.svg?branch=master)](https://travis-ci.org/slimta/python-slimta-celeryqueue)
[![Coverage Status](https://coveralls.io/repos/github/slimta/python-slimta-celeryqueue/badge.svg?branch=master)](https://coveralls.io/github/slimta/python-slimta-celeryqueue?branch=master)

Getting Started
===============

If you haven't yet installed [`python-slimta`][5], refer to the "Getting
Started" section. Once inside your virtualenv:

    (.venv)$ python setup.py develop

To run the suite of included unit tests:

    (.venv)$ py.test

Refer to the [API Documentation][2] and [Manual][3] for more information on
using this extension.

[1]: http://slimta.org/
[2]: http://docs.slimta.org/latest/api/extra.celeryqueue.html
[3]: http://docs.slimta.org/latest/manual/extensions.html#celery-queue
[4]: http://www.celeryproject.org/
[5]: https://github.com/slimta/python-slimta

