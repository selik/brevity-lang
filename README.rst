########################################################################
Brevity -- A programming language
########################################################################

.. pull-quote::

	"Brevity is the soul of wit"
		-- That Polonious guy.


Brevity is a pithy programming language. My goals for Brevity are to
keep the language simple and small, yet expressive and cross-platform,
with batteries included. To that end, it must be a LISP (or Lisp?) and
have a good package manager.

Unlike most Lisps, Brevity tries to use plain words that will be more
natural to a first-time programmer. Brevity minimizes jargon and
maximizes fun.

Brevity's standard library includes a style-formatter to help avoid
silly arguments over tabs versus spaces and a static analyzer with
inferred typing to help verify correctness.

Brevity aims for speed secondarily, but hopes to achieve C-like
efficiency through a just-in-time compiling interpreter and a habit of
relatively small "hot paths" through the code, to make good use of the
cache. To avoid branch mispredictions, Brevity encourages sorted data
structures and a high degree of polymorphism to enable algorithms with
few conditionals.

Perhaps most important for many of today's internet-first applications
are great tools in the standard library for building secure, scalable
web applications and APIs that make efficient use of datacenter
resources.

For practicality, Brevity has integrations with other programming
languages enabled through standard library modules.

*Note that these statements are wishful thinking, not reality.*


Copyright (c) 2017 Michael Selik.
