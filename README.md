# tucan-magnetics-mapping-export_20200129
The codes to make 3D plots of the magnetic field map and to export the map in a range defined by the user

- Mapping_0809_RUN1.csv
- Mapping_0809_RUN2.csv
- Mapping_0809_RUN3.csv
- Mapping_0809_RUN4.csv
--> Measurement data file of each 'RUN'.


- data_export.py
--> code to export data in a range selected by the user, the origin is defined such taht z=0 is the planned center of MSL-MSR


- plot_simple_cut_horizontal.py
--> code to make a 2D plot of each of the magnetic field componnet (Bx,By,Bz) at a cut plane x=const.
