# ETRS89-OSGB36-ETRS89-Conversions

## Python File

Contains two methods, one for converting between ETRS89 latitude and longitude to OSGB36 easting and northings as used in the UK, the second for doing the opposite (OSGB36 -> ETRS89)

## Javascript File

Converts ETRS89 latitude and longitude to OSGB36 Eastings and Northings for use with Express.

Send a latitude + longitude in the body, using 'lat' and 'lon' as the parameter names.

Returns easting and northing as JSON using e, n.

## Note:

Both the JS and Python scripts require the OSTN15.csv file to be present, this is used to perform the shift between ETRS89 eastings and northings and OSGB36 eastings and northings, and vice versa.
