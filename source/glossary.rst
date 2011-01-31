Glossary of Terms
=================

.. glossary::

   Application
      Twisted programs usually work with
      `twisted.application.service.Application`_. This class holds persistent
      configuration information for a runnable server—ports to bind to, places
      where connections must be kept or attempted, periodic actions to take and
      most everything else. It is the root object in a tree of services
      implementing IService_.
   Reactor
      The reactor is Twisted's event loop; it drives all applications which use
      Twisted. The reactor provides APIs for networking, threading, dispatching
      events, and more. See its `module documentation`_ for details.
   twistd
      The Twisted Daemon (``twistd(1)``) is a program that knows how to run an
      :term:`Application`. Though not strictly necessary to use an Application,
      ``twistd`` handles a lot of the boiler plate for you. twistd supports
      choosing a :term:`reactor`, logging to a logfile, daemonizing and more.
      See the *twistd docs* for more.
   WSGI
      Short for the `Web Server Gateway Interface`_, WSGI is a specification
      designed to allow Web and Application servers to communicate with Python
      applications. All modern Python web frameworks support the WSGI interface
      and it is the preferred method of deploying Python applications to the
      web.


.. _`Web Server Gateway Interface`: http://wsgi.org/wsgi/
.. _`twisted.application.service.Application`: http://twistedmatrix.com/documents/10.2.0/api/twisted.application.service.Application.html 
.. _`IService`: http://twistedmatrix.com/documents/10.2.0/api/twisted.application.service.IService.html
.. _`module documentation`: http://twistedmatrix.com/documents/10.2.0/api/twisted.internet.reactor.html
