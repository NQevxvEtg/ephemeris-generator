1. Download ephemeris directory and put it in the main directory
   ``` https://github.com/aloistr/swisseph/tree/master/ephe ```
  
2. Extract swetest program and put it in the main directory (Unix OS, for other OS see https://github.com/aloistr/swisseph/tree/master)
   ``` tar -xf swe_unix_src_2.10.03.tar.gz ```

3. Make sure you have all the required files and directories, see working_directory_structure.png

First generate a large ephemeris .csv file using generate_ephemeris.ipynb, 200 years should be good enough for most uses (approx.1.5 GB for a planet center)
Then use slim_ephemeris.ipynb to filter down the large .csv file for daily use 

![ephemeris](https://github.com/NQevxvEtg/ephemeris-generator/blob/main/helio-declination-Moon.png)
