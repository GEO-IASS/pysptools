# pysptools
Hyperspectral library for Python


Presentation
============

PySptools is the Python Spectral Tools project. It is hosted on
http://sourceforge.net/projects/pysptools/

You can go to the online documentation at http://pysptools.sourceforge.net/. The online documentation is updated regularly.

PySptools is a python module that implements spectral and hyperspectral algorithms. Specializations of the library are the endmembers extraction, unmixing process, supervised classification, target detection, noise reduction, convex hull removal and features extraction at spectrum level.

Dependencies
============

    * Python 2.7 or 3.x
    * Numpy, required
    * Scipy, required
    * scikit-learn, required
    * SPy, require, version >= 0.17
    * Matplotlib, required
    * CVXOPT, optional, to run FCLS
    * IPython, optional, if you want to use the display feature

The library is developed on the linux platform, with anaconda2-2.4.1 and anaconda3-2.4.1.


Installation
============

PySptools can run under Python 2.7 and 3.5. It has been tested for these versions but can probably run under others Python versions.

Note: The HSI cubes are, in general, large and the 64 bits version of Python is recommended.

The latest release is available at these download sites:

* pypi https://pypi.python.org/pypi/pysptools
* sourceforge http://sourceforge.net/projects/pysptools/ 

Manual installation
-------------------

To install download the sources, expand it in a directory and add the path of
the pysptools-0.xx.x directory to the PYTHONPATH system variable.

Distutils installation
----------------------

You can use Distutils. Expand the sources in a directory,
go to the pysptools-0.xx.x directory and at the command prompt type 'python setup.py install'.
To uninstall the library, you have to do it manually. Go to your python installation and in the
Lib/site-packages folder simply removes the associated pysptools folders and files.

Algorithms sources
==================

Matlab Hyperspectral Toolbox by Isaac Gerg, visit:
http://sourceforge.net/projects/matlabhyperspec/

The piecewise constant toolbox (PWCTools) by Max A. Little, visit:
http://www.maxlittle.net/software/

The Endmember Induction Algorithms toolbox (EIA), visit:
http://www.ehu.es/ccwintco/index.php/Endmember_Induction_Algorithms (broken?)

HySime by Bioucas-Dias and Nascimento, visit:
http://www.lx.it.pt/~bioucas/code.htm 

and science articles.


To run the test cases, download data1 and expand it in the pysptools directory. But this is
less true for the current version. The test cases will be reorganized in a future version.

In hope that this program is usefull.

Christian Therien
ctherien@users.sourceforge.net
