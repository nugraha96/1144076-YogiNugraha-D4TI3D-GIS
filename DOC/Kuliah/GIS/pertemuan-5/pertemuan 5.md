Background
In geographic information systems course there geospatial data, which in the geospatial data has a vector data and raster data. In vector data we can do create shapefile data.
Discussion
Ie non shapefile format topology efficient and simple that serves as a container for storing geometric location and attribute information from a geographic data.

How to create a shapefile using python:
Import shapefiles
input variable initialization, suppose x to shapefile.writer then written 'x = shapefile.writer ()'
In making the shapefile data, there are two formats for use.
SHP. Inside there are 3 types of SHP format shapefile
Point
polyline
Polygone
example shp => a.point (x, y, 0.0)

     2. DBF. In DBF there are three fields that are used, the first field contains the attribute table, the second field contains methods, the third field serves as a storage shapefile name that has been previously inputted.

example .dbf => a.field ( 'name.field', 'c', '40')
                          a.record ( 'bdg')

Geospatial data had been stored using the method a.save ( 'file.shp')

Explanation of the above method.
Point (x, y, 0.0) is entering data into the paint form and format shp ESRI.1 hruslah in the domain of x and y as the point coordinates.
Field ( 'name', 'c', '40') intention is to make the polygon attribute table 'name' of type varchar with length.
Record ( 'bdg') fill the table with value 'bdg'.

Conclusion
the conclusion is to add shapefiles using python very easy also the coding simple so that it can be remembered.

Suggestion
May the science that has been obtained about the create shapefiles can be used as much as possible so that the knowledge gained into useful knowledge.
