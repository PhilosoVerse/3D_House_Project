## 3D House Project

### Table of contents

* [General Information](General Information)
* [Approach](#Approach)
* [To Use](#To Use)


### General Information
- What -> we need you to build a solution with our data to model a house in 3D with only a home address.
- Why -> We are LIDAR PLANES , active in the Geospatial industy. We would like to use our data to launch a new branch in the insurrance business
- When -> from 6/7/20 9am untill 20/7/20 9am
- How -> using Pandas, Numpy, Matplotlib & other needed libaries 
- Who -> Steven Verkest (with some tips from other juniors from Becode)


### Approach
Connecting to an API to get lat& lon coordinates, so you can find the right tif file to search the address in, then cut out the information about the house.
Then plot it.

### Possible Improvements
- Optimize your solution to have the result as fast as possible.
-> divide 43 tif files into smaller tiles (39000+)
-> loop over the tiles to get the bounds and save the bounds in a csv file, to look up faster
- Features like the living area of the house in m², how many floors, if there is a pool, the vegetation in the neighborhood, etc...
- Better visualization.


### To use

Plot house of given address.

```
FINAL_CODE.ipynb
```




