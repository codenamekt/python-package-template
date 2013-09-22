##############################################################################
README: python-package-template
##############################################################################

******************************************************************************
Objective
******************************************************************************

To provide a solution that allows developers to take advantage of various
frameworks for dependancy resolution, testing, documentation, deployment, etc.
from the very first line of code.

******************************************************************************
Usage
******************************************************************************

1. Run `git clone git://github.com/vital-fadeev/python-package-template.git`
2. Write Your nice code.

******************************************************************************
Concept
******************************************************************************

* **One location for settings** - all settings specified in **setup.py** only
* **Simple usage** - one command: **make**

******************************************************************************
Features
******************************************************************************

* setup.py
    * rpm
    * deb
    * src
* testing
    * unittest
    * doctest
    * nose
    * tox
    * buildout?
* virtualenv - install and put package into it
* clean

******************************************************************************
More commands
******************************************************************************

* **make test** - run all tests
* **make deb** - build Debian package
* **make source** - build source tarball
* **make daily** - make daily snapshot
* **make install** - install program
* **make init** - install all requirements
* **make clean** - clean project, remove *.pyc and other templorary files
* **make deploy** - create vitrual environment

******************************************************************************
Based On
******************************************************************************

Package
http://jcalderone.livejournal.com/39794.html
http://guide.python-distribute.org/creation.html
http://www.debian.org/doc/packaging-manuals/python-policy/
http://www.producingoss.com/en/index.html
http://peak.telecommunity.com/DevCenter/setuptools
http://wiki.debian.org/Python/Packaging
https://github.com/srid/modern-package-template
https://github.com/kennethreitz/samplemod

******************************************************************************
TODO
******************************************************************************

* tox
* buildout?
* ipython for buildout
* automatically tests on all py for license, shabang, encoding, __ver__, etc.
* check openstack template for additional goodies
* distutils
* all docs in sphinx restructured txt and doc folder
* deployment test
* example code in all sections (pet object submodule, main dog/cat, object
  dane tests)

##############################################################################
README: python-package-template
##############################################################################

******************************************************************************
Objective
******************************************************************************

To provide a solution that allows developers to take advantage of various
frameworks for dependancy resolution, testing, documentation, deployment, etc.
from the very first line of code.

******************************************************************************
Usage
******************************************************************************

1. Run `git clone git://github.com/vital-fadeev/python-package-template.git`
2. Write Your nice code.

******************************************************************************
Concept
******************************************************************************

* **One location for settings** - all settings specified in **setup.py** only
* **Simple usage** - one command: **make**

******************************************************************************
Features
******************************************************************************

* setup.py
    * Distribute_.
    * rpm
    * deb
    * src
* tests - unittest, pytest
* .tar.gz - source generation
* .deb generation
* _.rpm generation\_
* virtualenv - install and put package into it

******************************************************************************
More commands
******************************************************************************

* **make test** - run all tests
* **make deb** - build Debian package
* **make source** - build source tarball
* **make daily** - make daily snapshot
* **make install** - install program
* **make init** - install all requirements
* **make clean** - clean project, remove *.pyc and other templorary files
* **make deploy** - create vitrual environment

******************************************************************************
Based On
******************************************************************************

# Package
[http://jcalderone.livejournal.com/39794.html
[http://guide.python-distribute.org/creation.html
[http://www.debian.org/doc/packaging-manuals/python-policy/
[http://www.producingoss.com/en/index.html
[http://peak.telecommunity.com/DevCenter/setuptools
[http://wiki.debian.org/Python/Packaging
[https://github.com/srid/modern-package-template

# Module
https://github.com/kennethreitz/samplemod

******************************************************************************
TODO
******************************************************************************

* tox
* buildout
* ipython for buildout
* automatically tests on all py for license, shabang, encoding, __ver__, etc.
* check openstack template for additional goodies
* distutils
* all docs in sphinx restructured txt
* deployment test
* example code in all sections (pet object submodule, main dog/cat, object
  dane tests)

.. _Distribute: http://mail.python.org/pipermail/python-dev/2009-October/
092678.html