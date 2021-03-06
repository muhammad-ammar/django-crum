Django-CRUM
===========

Django-CRUM (Current Request User Middleware) captures the current request and
user in thread local storage.

It enables apps to check permissions, capture audit trails or otherwise access
the current request and user without requiring the request object to be passed
directly. It also offers a context manager to allow for temporarily
impersonating another user.

It provides a signal to extend the built-in function for getting the current
user, which could be helpful when using custom authentication methods or user
models.

It is tested against:
 * Django 1.4.10 (Python 2.6 and 2.7)
 * Django 1.5.5 (Python 2.6, 2.7, 3.2 and 3.3)
 * Django 1.6.1 (Python 2.6, 2.7, 3.2 and 3.3)
 * Django 1.7b1 (Python 2.7, 3.2 and 3.3)
 * Django master (Python 2.7, 3.2 and 3.3)

[![Build Status](https://travis-ci.org/ninemoreminutes/django-crum.svg?branch=master)](https://travis-ci.org/ninemoreminutes/django-crum)
