movies2hdd
==========

A simple set of python scripts and libraries to work with movies. I use it with my DreamBox.

* Homepage: http://elchi.github.io/movies2hdd (It is empty.)
* Documentation of the API: http://elchi.github.io/movies2hdd/docs/html/ (generated using doxygen)

----------------------------------------------------------------------------

Why should I use it?

* It is written entirely in Python.
* It supports both 2.7 _and_ 3 _at the same time_. (!)
* It is a class.
* It is not finished.

----------------------------------------------------------------------------

How do I install it?

Just simply type `make install`.
You can run it via `movies2hdd`.

I'll try to provide a debian package for the next release.

----------------------------------------------------------------------------

Features:

* a CLI
	* a line-based interface
	* a GUI
	* a simple movie converter (.ts to .mpg, will delete additional audio tracks!)

* a library
	* connects to a DreamBox via FTP
	* searches for movies
	* downloads movies
	* filters meta data
	* queries thetvdb.com
	* converts the movies