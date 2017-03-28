.. SUSSA-SRT documentation master file, created by
   sphinx-quickstart on Wed Mar 15 15:17:34 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to SUSSA-SRT's documentation!
=====================================

Planning tools
--------------
+ CASTIA
+ basie (schedule creator)
+ Exposure Time Calculator

(Quicklook) Analysis Software in antenna
----------------------------------------
+ CASA
+ IDL + idlastro (http://idlastro.gsfc.nasa.gov/)
+ GILDAS
+ Miriad (http://www.atnf.csiro.au/computing/software/miriad/)
+ GBTIDL
+ Pulsar tools: 
    - presto
    - tempo
    - tempo2
    - PINT
    - sigproc
    - sixproc
    - dspsr
    - psrchive
+ NOD-3
+ PySDT - SRT Single Dish Tools (Imager, Calibrated light curves)
+ SuperMONGO

Data formats (to be?) supported
-------------------------------
+ nuragheFits
+ gildas
+ sdfits
+ psrfits
+ HDF5?

Catalogs
--------
+ psrcat
+ Flux and polarization calibrators


`Propose new software or data formats here! <https://goo.gl/forms/FPtCJnO3acdGksBA2>`__

Developer Documentation
-----------------------
This is the (in-development) developer documentation for the user support software at SRT

`See our Github repository, submit issues, interact! <https://github.com/sussa-srt/>`__

`Explore our working Docker images <https://hub.docker.com/u/sussa/>`__


Create a Docker container
~~~~~~~~~~~~~~~~~~~~~~~~~

+ First of all: learn by example! Check out `a few <https://github.com/sussa-srt/basecontainer>`__ `examples <https://github.com/sussa-srt/pulsarcontainer>`__.

+ Create a new repository in the SUSSA-SRT organization

+ Create a file called ``Dockerfile`` with the right instructions (see examples above).

+ Then, log in to `Docker Hub <https://hub.docker.com>`__, click on Create->Create Automated build->Github button->SUSSA-SRT->repository

+ Wait for the build to complete! Depending on the software packages you are compiling, it might take the time of a few coffees, including toasting and grinding each coffee bean.

.. toctree::
   :maxdepth: 2



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

