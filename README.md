OpenLDBSVWS Python Example
==========================

This repository contains examples of how to use the National Rail Live
Departure Boards Staff Version Web Service (OpenLDBSVWS), located at the
following URL:

* https://lite.realtime.nationalrail.co.uk/OpenLDBSVWS/

To use the service, you will need a token which is available by
signing up at the following URL:

* http://openldbsv.nationalrail.co.uk/

Edit `getDepartureBoardExample.py` and set `LDB_TOKEN` to your own token.

Install dependencies using `pip`:

`pip install -r requirements.txt`

Running `getDepartureBoardExample.py` will show you departures for
London Euston.

Updating the WSDL
-----------------

Periodically, a new version of the WSDL will be released at:

* http://lite.realtime.nationalrail.co.uk/OpenLDBSVWS/

This code is written for version 2021-11-01.  To update it to use a
later version, edit `getDepartureBoardExample.py` and change the `WSDL`
variable.  

Support
-------

This code has been tested on Python 3.10.4.

For support and questions with using the OpenLDBSVWS, please use the
forum at the following URL:
 
 * https://groups.google.com/group/openraildata-talk