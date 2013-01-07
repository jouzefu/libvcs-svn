libvcs-svn
==========

A tiny embeddable library for translating Subversion history.

This project is formed from the core of
[svn-dump-fast-export](https://github.com/barrbrain/svn-dump-fast-export).
That project has largely continued as
[a fork embedded in git.git](https://github.com/git/git/tree/master/vcs-svn).
The tests, front-ends and compatibility helpers from git-core are not included.

License
=======

This project is distributed under a two-clause BSD style license.

It once contained a derivative of
[Jason Evans' hash-based treap implementation](http://www.canonware.com/trp).
This is unnecessary with a bi-directional interface to the target VCS.

It is loosely derived from svndump-0.92, a parser in Java by Stefan Hegny
and others. This was a component of [SvnToCCase](http://svn2cc.sarovar.org).

The project is presently copyright:

* Jonathan Nieder
* David Barr
* Florian Achleitner
* Dmitry Ivankov
* Ramsay Jones
* Pete Wyckoff
* Michael Witten
