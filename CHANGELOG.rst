Changes
=======

Time flies!!
+++++++++++++++++++

0.3.6 (2012-06-08)
+++++++++++++++++++

* simplify code
* Trace method without data and files, according to RFC2612
* urlencode(data, 1) so that urlencode({'param': [1,2,3]}) => 'param=1&param=2&param=3'

0.3.5 (2012-04-24)
+++++++++++++++++++

* support specifying an IP for the request host, useful for testing API.

0.3.0 (2012-02-28)
+++++++++++++++++++

* python 3 compatible

0.2.2 (2012-02-22)
+++++++++++++++++++
* fix bug: file upload: file should always have a filename

0.2.1 (2012-02-22) 
+++++++++++++++++++

* more flexible file upload
* rename fetch2 to request
* add auth parameter, instead of put basic authentication info in url

0.1.2 (2011-12-07)
+++++++++++++++++++

* support basic auth

0.1 (2011-12-02)
+++++++++++++++++++

* first release
