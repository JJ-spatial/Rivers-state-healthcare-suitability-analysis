# Rivers-state-healthcare-suitability-analysis
Spatial analysis for identifying optimal hospital locations in Rivers State using GIS-based suitability modeling.
# Rivers State Healthcare Facility Siting

## Project Summary

This project focuses on identifying suitable locations for new hospitals in Rivers State using GIS. The goal is to move beyond just mapping data and actually support decision-making by showing where new healthcare facilities would make the most sense.

---

## Objective

The main aim was to answer a simple question:

Where should new hospitals be built in Rivers State?

To do this, I analyzed different spatial factors and combined them into a single suitability model.

---

## Approach

### Data Used

1) Road network (for accessibility considerations)
2) Settlements (to represent population distribution)
3) Elevation data (terrain)
4) Rivers State boundary

All datasets were cleaned, clipped to the study area, and projected properly before analysis.

---

### Suitability Analysis

I used a multi-criteria approach where different factors were considered:

1) Distance to major roads
2) Proximity to settlements
3) Terrain conditions

Each factor was converted into a raster, standardized, and then combined to produce a final suitability surface.

---

### Site Identification

From the final suitability map, I extracted the areas with the highest suitability values and identified potential locations for new hospitals within those zones.

---

## Output

The main output is a suitability map showing areas ranked from low to very high suitability for hospital development.

![Suitability Map](Rivers_Hospital_Suitability.png)

---

## Limitations

This analysis focuses mainly on spatial suitability. Accessibility was considered in a basic way (distance), and not through full road network travel-time analysis.

Data quality, especially for health facility locations, may also affect results.

---

## Next Steps

Planned improvements include:

* Adding proper network-based accessibility analysis
* Refining population representation
* Improving health facility data

---

## Tools

* QGIS
* OpenStreetMap data

---

## Author

GIS learner working towards practical, real-world spatial analysis skills.
