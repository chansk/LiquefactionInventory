Readme
Author: Alex Chansky, some code and methods from Michelle Meyer
Date: 3/26/21

DroppingFields.ipynb: Dropping additional fields if wanted. In particular, set up to delete Object ID field

DroppingNonLiqCells.ipynb: For 1 km, 100x100 m buffer polygon, identifies cells containing 1 or more liq point or poly, then drops all other cells.

DroppingOffshoreNonLiqPoints.ipynb: For all events, some points fall offshore, where DC = 0. These are deleted as we want to keep only onshore points for non-liquefaction sampling. As fishnet polygon is irrelevant for non-liq points, we can ignore polygon altogether.

ExportingData.ipynb: Exporting data from liq 1 km 100x100 m buffer shapefile of liq cells to CSV file.

ExtractLiqPtsData&DropBadData.ipynb

LiqEventsFishnets.ipynb

LiqEventsNonLiqCells01.ipynb: Erase 1km buff from 15km buff, then lay fishnet across space between them of 1.5x1.5 km. Results in a poly shapefile and a point shapefile (one point at centroid of each polygon).

LiqEventsNonLiqCellsBufferExtent02.ipynb: Determining X and Y mins and Maxes of buffer extents and place in CSV, which tells us where to place fishnets for both small and large buffers

MosaicASTER_02.ipynb:  Alex refa

MosaicASTER_DEMs.ipynb: 

MosaicClipping02.ipynb: Create new folder of quake name, extract DEM to PGA's extent and project. 
    Then, go into Downloads directly and use GDAL codes to create slope, TPI, TRI
    Then Use the last block of this code to project slope, TPI, and TRI into appropriate folders

MosaicClippingCTI.ipynb: 

MosaicCTIs.ipynb: 

MosaicDEMs.ipynb: 

ReclassEucDist.ipynb: 

SamplingNoLiqPts_NoLiqEvents.ipynb: 