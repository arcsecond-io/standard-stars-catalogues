Arcsecond's Standard Stars Catalogues
======

This repository is the data source of all Standard Stars catalogues of Arcsecond.io APIs.
Feel free to contribute by opening an Issue if you find a mistake, or to submit ideas of
new catalogues.

Why ?
====

Astronomical research enjoy tremendous amount of data stored in electronic format.
Yet, the standard stars catalogues are spread over websites, in static HTML pages,
two things we intend to solve here (two chores that Arcsecond is slowly tryingn to fix).

First, we would like to store them all, in a versionned respository to ensure
transparent history, in case of changes or corrections. The catalogues available
here have been found in the various pages of the websites of
[ESO](https://www.eso.org/sci/observing/tools/standards.html),
[Keck](https://www2.keck.hawaii.edu/inst/common/landolt_stds.html),
[UKIRT](http://www.ukirt.hawaii.edu/astronomy/),
[Gemini](https://www.gemini.edu/sciops/instruments/gmos/calibration/photometric-stds),
[IAC](http://catserver.ing.iac.es/landscape/index.php) and the
[NOT](http://www.not.iac.es/observing/forms/landscape/v1.4/www/)

Second, static HTML pages are again made for humans' reading. That is, data is
not decoupled from its comsumption.

So what ?
====

Two things will be built with these catalogues. First they will be made
available through REST *APIs* (data) at https://api.arcsecond.io/catalogues/
And second, a dedicated webpage with modern filtering tools will be
made available at https://www.arcsecond.io/catalogues/
