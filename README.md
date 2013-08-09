### [Project Homepage][1]
### [API Documentation][2] and [Manual][3]

--------------------

About
=====

Adds a [Celery][4] based queue extension to python-slimta. This queue is
intended to replace the built-in queuing mechanisms and allows for a more
distributed model of reception, storage and delivery.

[![Build Status](http://ci.slimta.org/job/python-slimta-celeryqueue/badge/icon)](http://ci.slimta.org/job/python-slimta-celeryqueue/)

Getting Started
===============

If you haven't yet installed [`python-slimta`][5], refer to the "Getting
Started" section. Once inside your virtualenv:

    (.venv)$ python setup.py develop

To run the suite of included unit tests:

    (.venv)$ nosetests

Refer to the [API Documentation][2] and [Manual][3] for more information on
using this extension.

[1]: http://slimta.org/
[2]: http://docs.slimta.org/en/latest/api/extra.celeryqueue.html
[3]: http://docs.slimta.org/en/latest/manual/extensions.html#celery-queue
[4]: http://www.celeryproject.org/
[5]: https://github.com/slimta/python-slimta

