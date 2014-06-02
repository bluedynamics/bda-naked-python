bda-nacked-python
=================

Buildout for Python.


This buildout installs fresh and clean Python versions on your computer.

If you use Debian-Linux, install the necessary packages first. For other OSes
do something similar::

  $ sudo apt-get install build-essential libreadline-dev zlib1g-dev libbz2-dev
  $ sudo apt-get install libssl-dev libjpeg-dev


Then bootstrap the buildout with your system's python version::

  $ python bootstrap.py


To install all versions, type::

  $ ./bin/buildout


To install a specific Python version, e.g. Python 2.6, type::

  $ ./bin/buildout -c buildout2.6.cfg


There will be links to the Python executables in the buildout's bin directory.
