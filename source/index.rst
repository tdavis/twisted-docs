Twisted Documentation
=====================

What is Twisted?
----------------

Twisted_ is Python_'s oldest and most comprehensive *asynchronous networking
engine*. In simple terms, this makes Twisted the ideal solution for creating a
variety of Internet servers and clients—from HTTP servers to IRC clients and
everything in between. Still under active development after a decade, Twisted
remains Python's best solution for a host of network-related tasks. You can
:ref:`read more about Twisted <about-twisted>`.

Why Use Twisted?
----------------

Like any piece of software, we must first answer why you would use Twisted. The
short answer is: **if you need a flexible, stable, well-tested framework
for creating highly-scalable Internet-based services, you need Twisted.** But
Twisted is more than a Framework: it's also a **library of components** built
using the very tools it gives you—tools *you* can use to easily and rapidly
create your own network-based services. Here are just a few examples of built-in
protocol implementations that include both server and client:

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

This only scratches the surface of Twisted's usefulness, though.


Still Not Convinced?
--------------------

That's okay! Twisted is *so* big and *so* malleable that it's often hard to
explain it much less convey how *you* can use it to create better software
systems. If you're not ready to :doc:`start understanding Twisted
<suiting-up>`, you should read about :ref:`Twisted's advantages
<advantages>` and check out :ref:`who's using Twisted <success-stories>`.


Ready to Get Started?
---------------------

Once you're intrigued enough to start down the *Twisted Path*, you should begin
by :doc:`suiting up <suiting-up>`—that is, become familiar with Twisted's basic
structure, philosophies, and quirks. We know all you probably just want to find
out how to solve a specific problem with Twisted (or find out if one of its
:doc:`projects <projects/index>` solves it for you), but a little effort up
front will go a long way in understanding the tutorials and code samples you're
*really* looking for.

Properly attired (or sufficiently stubborn, as the case may be), you'll be ready
to :doc:`dive in <diving-in>` (to continue the lame water-based analogy).
You'll learn how to implement increasingly complex applications using Twisted
and eventually move on to ...


Table of Contents
=================

Base Documentation
------------------

.. toctree::
   :maxdepth: 2

   why-twisted
   suiting-up
   diving-in
   meta

Project Documentation
---------------------

.. toctree::
   :maxdepth: 3

   projects/index


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


.. _Twisted: http://twistedmatrix.com
.. _Python: http://python.org
