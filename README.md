# Detecting nearshore bathymetry from ICESat-2 ATLO3 returns around Aasiaat, Greenland and Nuuk, Greenland

## Background
Nearshore bathymetry is difficult to obtain due to boat-based traditional sampling methods - essentially, sampling is limited to how close to shore a boat can go before getting stuck or risking damage. Therefore, drone or satellite based LiDAR is one of the only used to sample the region closest to the shore. ICESat-2, launched in 2018, has a green laser that can penetrate up to 30 m depth. 

## Dataset
[ATL03 Download](https://nsidc.org/data/atl03)

"This data set (ATL03) contains height above the WGS 84 ellipsoid (ITRF2014 reference frame), latitude, longitude, and time for all photons downlinked by the Advanced Topographic Laser Altimeter System (ATLAS) instrument on board the Ice, Cloud and land Elevation Satellite-2 (ICESat-2) observatory. The ATL03 product was designed to be a single source for all photon data and ancillary information needed by higher-level ATLAS/ICESat-2 products."


## Scope of Project
The larger scientific question concerns coverage of ICESat2 bathymetry: where is bathymetry visible and can you automate the process of finding it?  I will first perform a refraction correction on the data to correct for the change in refraction index as the laser travels through the water column and further correct the altimetry data to be referenced to the geoid. I will plot coverage maps around areas of interest and compare ATL03 and ATL13 returns. 
