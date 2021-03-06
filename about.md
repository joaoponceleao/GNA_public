---
layout: page
title: About
---

# The GNA Project
---

The GNA (Geographic Network Analysis) Project.

## Technology
---

The GNA Project takes advantage of various open-source projects, primarily:

* [PostgreSQL](http://www.postgresql.org)
* [PostGIS](http://postgis.net)
* [Django & GeoDjango](https://www.djangoproject.com)
* [Python](https://www.python.org)
* Geospatial libraries
    * [GEOS](http://trac.osgeo.org/geos/)
    * [GDAL](http://www.gdal.org)
    * [geopy](https://github.com/geopy/geopy)
* Python libraries
    * [django-rest-framework](http://www.django-rest-framework.org)
    * [django-rest-framework-gis](https://github.com/djangonauts/django-rest-framework-gis)
    * [django-mptt](https://github.com/django-mptt/django-mptt/)
    * [django-nvd3](https://github.com/areski/django-nvd3)
    * [Pillow](http://python-pillow.github.io)
    * [python-nvd3](https://github.com/areski/python-nvd3)
    * [psycopg2](http://initd.org/psycopg/)
* [Leaflet](http://leafletjs.com)
* [Leaflet.draw](https://github.com/Leaflet/Leaflet.draw)
* [jQuery](http://jquery.com)

## Acknowledgments
---

The project has benefited from the open-source community and the works of others.
It has either implemented, based parts of its code on, or simply taken inspiration from the following projects:

* Several open-source projects by [Makina Corpus](http://makina-corpus.com)
* The [GeoNode project](http://geonode.org)
* The RENCI (Renaissance Computing Institute) [Geoanalytics Platform](http://renci.org/research/geoanalytics-framework/)

## Changes
---

* v0.0.2, 18/08/2014 -- Initial alpha release.
    - Implemented release cycle numbering.
    - Released .core module
        + Added API and utilities in .core
        + Added Django Rest Framework for building API
        + Added DRF-GIS for geojson support in API
        + Confirmed API support for future release of ol3.js
    - Released .units module
        + Added geocoding and reverse geocoding through geopy
        + Started implementing exceptions
        + Added geos.centroid for calculating locations
    - Initial release of .taxonomy module
        + Added initial fixtures
    - Initial release of .metadata module
        + Added Primary Data and Conditions.choices
    - Project-wide:
        + Added AJAX in mapping views
        + Added Django Bower for managing /components/bower_components
        + Added Crispy Forms for managing Bootstrap 3
        + Added Leaflet.js and Leaflet.draw for mapping
    - Miscellaneous
        + Initial release of vagrant settings
        + Cleaned up directory structure and some code
        + Cleaned up python requirements
