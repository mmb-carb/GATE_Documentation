# The Basic Science in GATE - UNDER CONSTRUCTION


## Photochemic Modeling on a 3D Grid

The purpose of the GATE model is to grid aircraft emissions for photochemical modeling.<sub>1</sub>  Photochemical modeling is the computational process of calculating atmospheric chemistry on a 3D grid given a complete set of air pollutants and meteorology. Typically, the grid is a regular, nearly square grid in the latitude and longitude directions, with grids from 1km to 36km on edge.<sub>2</sub> In the vertical direction, the 3D grid tends to be smaller near the ground, where people are most interested in accuracy, and much larger aloft. The aim of the GATE model is to correctly place aircraft emissions in such a 3D grid.

To create gridded, 3D aircraft inventories, the GATE process begins with an emissions inventory.<sub>3</sub> Emissions inventories contain ungridded, sometimes annual, emissions from an airport, by vehicle category. In particular, emissions inventories record aircraft emissions up to about 1km in altitude.<sub>4</sub> These ungridded emissions need to be divided into hourly pieces and accurately placed into 3D grid cells. Aircraft pose a particular problem for inventory gridding, as their emissions are fundamentally more three dimensional than typical area and point sources. As such, aircraft emissions have usually been given a fairly light treatment.

![Figure 1: 3D allocation of LAX PM Emissions, pre-GATE](resources/LAX_2012_PM_one_lego.png)
*Figure 1: 3D allocation of LAX PM Emissions, pre-GATE*

Figure 1 above shows how emissions from Los Angeles International airport (LAX) have typically been distributed in past photochemical models. Emissions are simply placed into a grid cell that covers the geometric centroid of the airport, and possibly one or two grid cells above from that. Without specialized aircraft modeling, the best that was achievable prior to GATE was to model airports as a single point source (that is, with a geometry much like a coal power plant). The goal of the GATE model is to take the next step in improving the realism of how aircraft are portrayed in photochemical modeling.


## 3D Flight Paths

> Coming Soon

1. Describe runway information gathering (AirportIQ ref). Show LAX plot and discuss taxiing emissions.
2. Discuss take-off and landing angles / flight paths.  (refs)
3. Discuss wireframe model of a runway / airport. Show plot.


## Intersecting Flight Paths with a 3D Grid

> Coming Soon

1. Discuss intersecting above wireframe with grid.  Discuss problem complexity.
2. Give mathematical approach to solution (ref).
3. Show LAX spatial surrogates (3 x stage), for one runway. Discuss.


## Applying this to Emissions Inventories

> Coming Soon

1. Discuss splitting aircraft emissions by flight stage. (refs)
2. Show final LAX plot (all runways and stages) and discuss.
3. Discuss improvements?  (grid intersect and EDMS for stage)


## Temporal Profiles

> Coming Soon

1. Show temporal analysis from BTS (ref) commercial flight data.
2. Show example temporal profiles


[Back to Main Readme](../README.md)


## References

1. [US EPA page on Photochemical Modeling](https://www3.epa.gov/scram001/photochemicalindex.htm)
2. [TCEQ 2006 SIP Document - Chapter 2: Photochemical Modeling](http://www.tceq.texas.gov/assets/public/implementation/air/sip/hgb/hgb_sip_2006/06027SIP_proCh2.pdf)
3. [US EPA NEI homepage](https://www.epa.gov/air-emissions-inventories/national-emissions-inventory-nei)
4. [Aircraft Emissions Inventory for Texas Statewide 2014 AERR Inventory and 2008 to 2040 Trend Analysis Years](https://www.tceq.texas.gov/assets/public/implementation/air/am/contracts/reports/ei/582155160603FY1508-20160516-erg-2014_AERR_Inventory_Aircraft_Revised.pdf)


[Back to Main Readme](../README.md)
