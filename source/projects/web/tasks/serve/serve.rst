Serving HTML
------------

.. highlight:: sh

Serving a directory of HTML is almost as simple with :term:`twistd` as it is
with the venerable ``python -m SimpleHTTPServer``::

   twistd web --path /path/to/web/content

You can provide expandable paths, too::

   twistd web --path ~/public_html/

You can stop the server at any time by going back to the directory you started
it in and running the command::

   kill `cat twistd.pid`

Other configuration options are available; run ``twistd web --help`` to see
them all.


Serving WSGI Applications
-------------------------

The easiest way to start serving :term:`WSGI` applications is, again, with
:term:`twistd`::

   twistd -n web --wsgi=helloworld.application

This assumes a WSGI application callable named ``application`` in a
``helloworld`` module/package, which might look like:

.. code-block:: py

   def application(environ, start_response):
       """Basic WSGI Application"""
       start_response('200 OK', [('Content-type','text/plain')])
       return ['Hello World!']

