# Detecting nearshore bathymetry from ICESat-2 around Aasiaat, Greenland

## Background
Nearshore bathymetry is difficult to obtain due to boat-based traditional sampling methods - essentially, sampling is limited to how close to shore a boat can go before getting stuck or risking damage. Therefore, drone or satellite based LiDAR is one of the only used to sample the region closest to the shore. ICESat-2, launched in 2018, has a green laser that can penetrate up to 30 m depth. 

## Dataset
[ATL03 Download](https://nsidc.org/data/atl03)

"ATL03 contains height above the WGS 84 ellipsoid (ITRF2014 reference frame), latitude, longitude, and time for all photons downlinked by the Advanced Topographic Laser Altimeter System (ATLAS) instrument on board the Ice, Cloud and land Elevation Satellite-2 (ICESat-2) observatory. The ATL03 product was designed to be a single source for all photon data and ancillary information needed by higher-level ATLAS/ICESat-2 products."

[ATL13 Download](https://nsidc.org/data/atl13)

"ATL13 contains along-track water surface heights and descriptive statistics for inland water bodies. Water bodies include lakes, reservoirs, bays, and estuaries. Descriptive statistics include ... coarse depth to bottom topography"

## Scope of Project
The larger scientific question concerns coverage of ICESat2 bathymetry: where is bathymetry visible and can you automate the process of finding it using ATL13? ANalysis includest coverage maps around areas of interest and compare ATL03, ATL06, ATL08, and ATL13 returns. 

https://mybinder.org/v2/gh/cescherbrayton/rces-final-project/tree/master/HEAD
