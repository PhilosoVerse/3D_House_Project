# 3D_House_Project
becode training project 1

What -> we need you to build a solution with our data to model a house in 3D with only a home address.
Why -> We are LIDAR PLANES , active in the Geospatial industy. We would like to use our data to launch a new branch in the insurrance business
When -> from 6/7/20 9am untill 20/7/20 9am
How -> using Pandas, Numpy, Matplotlib & other needed libaries 
Who -> Steven Verkest (with some tips from other juniors from Becode)

Pending things to do ->
#Optimize your solution to have the result as fast as possible.
-> divide 43 tif files into smaller tiles (39000+)
-> loop over the tiles to get the bounds and save the bounds in a csv file, to look up faster
#Features like the living area of the house in m², how many floors, if there is a pool, the vegetation in the neighborhood, etc...
-> did not have time for it
#Better visualization.
-> did not have time for it


LOGBOOK:
- 6/7/20 untill 8/7/20   -> read about project ; general research & exloration ; find libraries to open tiff files & shp files ; download all project data
- 9/7/20 untill 10/9/20  -> able to look up an address sending a request to an API ; discovered that bounds of tif file had lamber-72 coordinates ; able to crop a part of a                                 tiff file in a smaller piece
- 13/7/20                -> made the code do: get address coordinates, compare coordinates with tif file, open matching tif file
- 14/7/20                -> cutted the tiff files in 39000+ tiles, to make it look up faster, putted the bound values in a csv file
- 15/7/20                -> discovered i could use a request to get the shape file info to be able to plot an address
- 16/7/20 untill 18/7/20 -> trying to fix errors regarding "Windows do not overlap Error" 

