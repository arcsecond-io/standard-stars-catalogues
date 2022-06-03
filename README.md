Arcsecond's Standard Stars Catalogues
======

This repository is the data source of all Standard Stars catalogues of [Arcsecond.io](https://api.arcsecond.io).
Feel free to contribute by opening an Issue if you find a mistake, or to submit ideas for
new catalogues.

Why ?
====

Astronomical research enjoy tremendous amount of data stored in electronic format.
Yet, the standard stars catalogues are spread over websites, in static HTML pages,
two things we intend to solve here (two chores that Arcsecond is slowly trying to fix).

First, we would like to store them all, in a versionned respository to ensure
transparent history, in case of changes or corrections. The catalogues available
here have been found in the various pages of the websites of
[ESO](https://www.eso.org/sci/observing/tools/standards.html),
[Keck](https://www2.keck.hawaii.edu/inst/common/landolt_stds.html),
[UKIRT](http://www.ukirt.hawaii.edu/astronomy/),
[Gemini](https://www.gemini.edu/sciops/instruments/gmos/calibration/photometric-stds),
[IAC](http://catserver.ing.iac.es/landscape/index.php) and the
[NOT](http://www.not.iac.es/observing/forms/landscape/v1.4/www/).

Second, static HTML pages are again made for humans' reading, which is
good for some cases. Yet, it is hard to build anything from it since data
is mixed with presentation. That is, data is not decoupled from its comsumption.

By keeping all catalogues in a simple text format, yet organised and homogenized
inside this repository, adding some metadata, make possible to use all this information
as data.

What next?
====

These catalogues data are made available through REST *APIs* at https://api.arcsecond.io/catalogues/.

Second, an endpoint dedicated to Standard Stars search can be found at https://api.arcsecond.io/standardstars/ with the
query params:

* `around=<RA in decimal degrees,Dec in decimal degrees>`
* `count=<integer>` (optional, default to 5, max to 10).

And last but not least, dedicated webpages with modern filtering tools are made available at 
https://www.arcsecond.io/catalogues/ for catalogues and a complete and free Standard Stars Browser
is made available at https://www.arcsecond.io/standardstars/ .

# The full list:

* [Casali 1992: UKIRT Faint Standards](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Casali_1992)
* [Cohen et al. 1999: ESO Mid-Infrared Standard Stars](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Cohen_etal_1999)
* [ESO InfraRed Telluric: ESO Infra-Red Telluric Standards](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/ESO_InfraRed_Telluric)
* [Gehrels 1974: Unpolarized and Polarized Standard Stars](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Gehrels_1974)
* [Hamuy et al. 1992 & 1994: Spectrophotometric Standards](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Hamuy_etal_1992_1994)
* [Hunt et al. 1998: JHK Photometric Standards Catalogue](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Hunt_etal_1998)
* [Landolt 1992: Faint UBVRI Standard Stars](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Landolt_1992)
* [Leggett et al. 2003 2006: UKIRT MKO ZYJHKL'M Photometric Standards](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Leggett_etal_2003_2006)
* [Massey et al. 1998: Kit Peak Spectrophotometric Standard Stars](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Massey_etal_1998)
* [Oke 1990: Faint Spectrophotometric Standard Stars](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Oke_1990)
* [Perryman et al. 1997: Hipparcos catalogue, spectroscopic telluric standard stars](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Perryman_etal_1997)
* [Persson et al. 1998: Photometric Standards](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Persson_etal_1998)
* [Stone 1977: Spectrophotometric Standards](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Stone_1977)
* [Stone 1996: HST Spectrophotometric Standards](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Stone_1996)
* [Tokunaga 1986: Bright Infrared Standard Stars at 10 and 20 microns](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Tokunaga_1986)
* [Turnshek et al. 1990: HST photometric, spectrophotometric, and polarimetric calibration objects](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Turnshek_etal_1990)
* [Whittet et al. 1992: Polarized Stars](https://github.com/arcsecond-io/standard-stars-catalogues/tree/master/Whittet_etal_1992)
