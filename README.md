Sunrise/Sunset Web Service
--------------------------

This project provides a simple web service that will produce a table of sunrise/sunset times
based on lat/lon.

The name of the script is `getsun`; usage is as follows:

    http://www.example.com/what/ever/getsun/1997,35.6008,-82.5542,US/Eastern

The above request will respond with a table of sunrise/sunset times
for the year 1997 for the given latitude and longitude, expressed in
the 'US/Eastern' timezone.

This program uses python and requires on the python `ephem` and `pytz`
modules, which are readily available in python package management
systems, or in many operating system repositories.  (For example, on
CentOS, you can type `yum install ephem pytz` to install both of
them.)
