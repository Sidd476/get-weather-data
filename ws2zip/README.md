### ws2zip: Find nearest zip codes given a list of weather stations

Default: Gets 5 nearest zip codes for GHCND or COOP weather station files. The files contain latitude and longitude of the weather stations, and we find the nearest zip codes via Geonames.

* [COOP Station List](coop-stations.txt). For current list, see the [NCDC Site](http://www.ncdc.noaa.gov/homr/reports/platforms;jsessionid=794891457456A71118A5D0D81CA80100)
* [GHCND Station List](ghcnd-stations.txt). For current list, see the [NCDC Site](http://www.ncdc.noaa.gov/homr/reports/platforms;jsessionid=794891457456A71118A5D0D81CA80100)

#### Requirements
Depends on [geonames](https://github.com/ashchristopher/python-geonames)

#### Usage
For file names expected, see the end of the script.
<pre>python weather.py</pre>



