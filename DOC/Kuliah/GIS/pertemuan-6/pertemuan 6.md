
Background
In GIS (geographic information system) there is a shapefile, shapefile is a geometric data that can be added, edited, deleted and viewed.
How do I create a shapefile?
How do I edit shapefile?
How do I delete a shapefile?
How do I show shapefile?
Discussion
How to create a shapefile geometry data is as follows:
--Buka Python at the command prompt
--import shapefile
--sf = shapefile.Writer (shapeType = 1)
--sf.shapeType -> to check
--sf.field ( 'NAME', 'C', '40')
--sf.field ( 'OWNER', 'C', '40')
--sf.record ( 'Warteg', 'Jadon Kusendar')
--sf.point (10,10,0,0) -> here point line or polygon can be changed as desired
--sf.save ( 'warteg.shp') -> to store
How to edit the shapefile geometry data is as follows:
--Buka Python at the command prompt
--import shapefile
--sf = shapefile.Editor (shapefile = 'warteg.shp')
--sf.point (19,19,0,0)
--sf.record ( 'Warung Padang', 'Ucok')
--sf.save ( 'warteg')
How to remove the geometry data from shapefiles are as follows:
--Buka Python at the command prompt
--import shapefile
--e = shapefile.Editor ( 'warteg.shp')
--e.shape (1) -> to record how much
--e.delete (1)
--e.save ( 'warteg')
How to display data shapefile geometry is as follows:
--Buka Python at the command prompt
--import shapefile
--sf = shapefile.Reader ( 'warteg.shp')
--sf.record () -> all the records
--sf.record (0) -> record to 1
--sf.record (1) -> record to 2
--sf.shapes () (0) .points -> Show
Cover
The conclusion that the shapefile geometry data you can conduct adding, editing, deleting and viewing geometry data from shapefiles with ease using python.
Suggestions We recommend that you can learn how to create, edit, delete and display data shapefile as easily and simply using python programming and can utilize the knowledge acquired.
