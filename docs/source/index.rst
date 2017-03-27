.. SUSSA-SRT documentation master file, created by
   sphinx-quickstart on Wed Mar 15 15:17:34 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to SUSSA-SRT's documentation!
=====================================
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
    - sigproc
    - sixproc
    - dspsr
    - psrchive
+ NOD-3

Data formats to be supported
----------------------------
+ nuragheFits
+ gildas
+ sdfits
+ psrfits

Catalogs
--------
+ psrcat
+ Calibratori in flusso e polarizzazione.

Development guide
-----------------
This is the (in-development) developer documentation for the user support software at SRT

`See our Github repository, submit issues, interact! <https://github.com/sussa-srt/>`__

`Explore our working Docker images <https://hub.docker.com/u/sussa/>`__

Developer Documentation
-----------------------
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

Riunione MWP3 - 15/09/2015

presenti: Poppi, Carretti, Buttu, Fara, Burgay, Castangia, Tarchi, Pellizzoni.

- Sito SRT. E' necessario procedere con un aggiornamento delle informazioni contenute nel sito. Sara' il punto di riferimento per l'utenza esterna. Aggiungere la squadra operativa invece di "STAFF".

- Elenco tools e sw per gli osservatori. Rivisto elenco definito in AV (http://scicomsrt.pbworks.com/w/page/52377336/SOFTWARE%20TOOLS%20AT%20THE%20TELESCOPE). L'elenco verra' inserito nella sezione "ASTRONOMERS" secondo questa struttura.


a) Observing Tools:
  1) Web page per sottomissione proposal. Si valuta di procedere con una sistema integrato nel sito web di SRT, utilizzando lo stesso framework. Alla sottomissione, viene generato un codice identificativo della proposal: 'S' seguito da un numero progrsessivo costituito da 4 cifre. Esempio S0001.
  2) Schedule maker
  3) Source Visibility
  4) Exposure time calculator (ETC)
  5) Opacity Forecast (Chiedere a F.Buffa)
  6) Opacity Calculator

b) Formato dati supportati.
  1) nuragheFits (link a documento specifiche)
  2) gildas
  3) sdfits
  4) psrfits

b2 e b3 sono nativi per quanto riguarda i BE roach, per XArcos  tramite convertitori

c) Data Tools e Fruizione dei dati

Per quanto riguarda il SRT Single Dish imager tool, gli sviluppatori devono definire la licenza d'uso in modo da definire le modalita' con cui gli utenti esterni potranno eventualmente usufruire del tool (RIf. Alberto). In ogni caso non viene data la possibilita' di scaricare il tool, ma viene creata una pagina di descrizione del tool, con i riferimenti per ulteriori informazioni.

I dati saranno fruibili a SRT per 24 ore. Successivamente verranno trasferiti in OAC   e pertanto i tool di analisi dati saranno tali da permettere un quick look o una preanalisi del dato per valutare come si stanno svolgendo le osservazioni.
Il quicklook o preriduzione verra' fatta da nuraghe-obs2. User id di lognin sara' i l project code (vedi a1). Al login verranno montati i dischi e le directory dati definite dal project id. Al logout, verranno smontati tale directory.

Rimosso aips dall'elenco dei tools. Elenco tools:

  1) CASA -verificare quale versione stabile e quale devel e' necessaria. Action Alberto)
  2) IDL + idlastro (http://idlastro.gsfc.nasa.gov/)
  3) GILDAS - verificare versione per spettroscopia (Tarchi) e  per olografia (Sergio)
  4) Miriad - aggiornare a versione ATNF http://www.atnf.csiro.au/computing/software/miriad/
  5) GBTIDL
  6) Pulsar tools (presto, tempo, tempo2, sigproc, sixproc, dpsr, psrchive). Verificare quali sono le versioni da installare   (Marta).

d) Catalogs
  1) psrcat
  2) Calibratori in flusso e polarizzazione.





















