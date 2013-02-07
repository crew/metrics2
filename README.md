Metrics2
===========

This rewrite of metrics will use a few new technologies

Aggregator
----------

The aggregator will pull data from the sources of logs (/proj), wtmp and send
send PUT requests to the appropriate place.

Backend
---------
It seems couchDB can be out backend considering it does everything over HTTP. We
have to establish a schema that the aggregator will use.

Frontend
--------
Some kind of javascript graphing library will have to do

