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


Lanyon is an unassuming [Jekyll](http://jekyllrb.com) theme that places content first by tucking away navigation in a hidden drawer. It's based on [Poole](http://getpoole.com), the Jekyll butler.

### Built on Poole

Poole is the Jekyll Butler, serving as an upstanding and effective foundation for Jekyll themes by [@mdo](https://twitter.com/mdo). Poole, and every theme built on it (like Lanyon here) includes the following:

* Complete Jekyll setup included (layouts, config, [404](/404), [RSS feed](/atom.xml), posts, and [example page](/about))
* Mobile friendly design and development
* Easily scalable text and component sizing with `rem` units in the CSS
* Support for a wide gamut of HTML elements
* Related posts (time-based, because Jekyll) below each post
* Syntax highlighting, courtesy Pygments (the Python-based code snippet highlighter)

### Lanyon features

In addition to the features of Poole, Lanyon adds the following:

* Toggleable sliding sidebar (built with only CSS) via **☰** link in top corner
* Sidebar includes support for textual modules and a dynamically generated navigation with active link support
* Two orientations for content and sidebar, default (left sidebar) and [reverse](https://github.com/poole/lanyon#reverse-layout) (right sidebar), available via `<body>` classes
* [Eight optional color schemes](https://github.com/poole/lanyon#themes), available via `<body>` classes

[Head to the readme](https://github.com/poole/lanyon#readme) to learn more.

### Browser support

Lanyon is by preference a forward-thinking project. In addition to the latest versions of Chrome, Safari (mobile and desktop), and Firefox, it is only compatible with Internet Explorer 9 and above.

### Download

Lanyon is developed on and hosted with GitHub. Head to the <a href="https://github.com/poole/lanyon">GitHub repository</a> for downloads, bug reports, and features requests.

Thanks!
