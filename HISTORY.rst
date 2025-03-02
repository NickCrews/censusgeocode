0.5.1
-----

* Fix empty default values (#23)

0.5.0
-----

* Removed hard-coded benchmarks and vintages, which were out of date. Refer to Census Geocoder documentation for a list of active benchmarks and vintages.

0.4.4
-----

* Handle misformatted batch responses from the Census
* Add more options for command line tool
* Codify support for Python 3.7, 3.8. Drop support for Python 3.4

0.4.3
-----

* Fixed bug in parsing addressbatch results in some versions of Python (thanks @summonholmes)

0.4.2
-----

* Fix reversed coordinate order in batch addresses

0.4.1
-----

* Add static methods to module
* Update vintages and benchmarks.

0.4.0
-----

* Add support for address batch functionality, including to command line tool

0.3.0
-----

* Better error reporting when API is down.
* Use `requests[security]` to fix SSL 3 errors, bump required `requests` version.
* Combine Py 2 and Py 3 codebases.
* Add timeout parameter to `CensusGeocode.fetch` (thanks @mxr)

0.2.3
-----

* Always yield a `ValueError` when Census API is broken.
* Internal refactor to simplify keyword arguments.

0.2.2
-----

* Improve deployment and fix readme

0.2.1
-----

* Add command line tool
