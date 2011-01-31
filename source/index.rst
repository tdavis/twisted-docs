Twisted Documentation
=====================

What is Twisted?
----------------

Twisted_ is Python_'s oldest and most comprehensive *event-driven networking
engine*. In simple terms, this makes Twisted the ideal solution for creating a
variety of Internet servers and clients—from HTTP servers to IRC clients and
everything in between. Still under active development after a decade, Twisted
remains Python's best solution for a host of network-related tasks. You can
:ref:`read more about Twisted <about-twisted>` or just keep reading this page to
learn how it can help you.


Why Use Twisted?
----------------

As with any piece of software, we must first answer why you would use Twisted.
One answer is: **if you need a flexible, stable, well-tested framework for
creating highly-scalable Internet-based services, you need Twisted.** But
Twisted is more than a Framework! It's also a **comprehensive library of
components** built using the very tools it gives you—tools *you* can use to
easily and rapidly create your own network-based services. Here are just a few
examples of built-in protocol implementations that include both server and
client:

* SSH/SFTP
* HTTP
* SMTP, IMAP and POP
* DNS
* NNTP
* Chat/IM

Twisted's long history has led to countless other protocols being implemented
(many quickly and easily) using its core software. So whether you want to
securely talk to a server, publish a web site, send and receive email, create a
chat bot, control machine processes, or a host of other things, Twisted has you
covered. And thanks to its flexibility, you can also *change* any of these
components to suit your specific needs using just Python!

This only scratches the surface of Twisted's usefulness, though. To learn more
about what makes Twisted uniquely useful and generally great, you should read
about :ref:`Twisted's advantages <advantages>` and check out :ref:`who's using
Twisted <success-stories>`.

**SPOILER**: Twisted is one-of-a-kind and trusted by the likes of :ref:`NASA
<success-nasa>`, :ref:`Lucas Films <success-lucas>`, :ref:`Justin.tv
<success-justintv>`, :ref:`TweetDeck <success-tweetdeck>` and thousands of other
companies and individuals!


Still With Us?
--------------

That's great! Twisted is *so* big and used in such a wide variety of ways that
it takes a good deal of time to fully explore. The good news is, you don't need
to know all of Twisted in order to use it *right now* to solve a bunch of common
(and uncommon) problems.


Task-based Documentation
^^^^^^^^^^^^^^^^^^^^^^^^

Below is a list of *Tasks*. Each Task is something Twisted already has a core
project for. In many cases, a few lines of code will get you a full solution to
your problem. In other cases, a complex task can be accomplished by combining
numerous smaller solutions. Here some common tasks we've chosen to highlight;
each individual Twisted Project has its own tutorials.

.. toctree::
   :maxdepth: 1

   projects/web/tasks/serve/index


Project Documentation
^^^^^^^^^^^^^^^^^^^^^

If you don't see your specific task on the list but some of them fall into the
general protocol (or other ballpark) you're interested in, you should consult
the appropriate Project Documentation:

.. toctree::
   :maxdepth: 3

   projects/index


Base Documentation
^^^^^^^^^^^^^^^^^^

If a Twisted solution to your problem still eludes you, it's likely you'll need
to implement your own Application, Protocol, or other chunk of code. The first
step is to get to know Twisted (*suiting up*). Once you've got the core
concepts, you'll have no trouble bending it to your whim (*diving in*)!

.. toctree::
   :maxdepth: 2

   suiting-up
   diving-in

TODO: Needs fleshing.


Everything Else
---------------

Everything else you wanted (or didn't want) to know about Twisted can be found
below.

.. toctree::
   :maxdepth: 2

   why-twisted
   meta


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


.. _Twisted: http://twistedmatrix.com
.. _Python: http://python.org

