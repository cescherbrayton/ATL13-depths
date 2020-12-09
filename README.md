# Detecting nearshore bathymetry from ICESat-2 ATLO3 returns around Aasiaat, Greenland 

## Background
Nearshore bathymetry is difficult to obtain due to boat-based traditional sampling methods - essentially, sampling is limited to how close to shore a boat can go before getting stuck or risking damage. Therefore, drone or satellite based LiDAR is one of the only used to sample the region closest to the shore. ICESat-2, launched in 2018, has a green laser that can penetrate up to 30 m depth. 

## Dataset
[ATL03 Download](https://nsidc.org/data/atl03)

"This data set (ATL03) contains height above the WGS 84 ellipsoid (ITRF2014 reference frame), latitude, longitude, and time for all photons downlinked by the Advanced Topographic Laser Altimeter System (ATLAS) instrument on board the Ice, Cloud and land Elevation Satellite-2 (ICESat-2) observatory. The ATL03 product was designed to be a single source for all photon data and ancillary information needed by higher-level ATLAS/ICESat-2 products."


## Scope of Project
I will first perform a refraction correction on the data to correct for the change in refraction index as the laser travels through the water column. I will further correct the altimetry data to be referenced to the geoid. My plots will include a repeat track plot of each pass over the region; an altimetry profile featuring bathymetric features with reference tracks; a coverage map of where bathymetry is present in the region; a comparison with MBES data collected in Aasiaat and other bathymetric datasets.  
