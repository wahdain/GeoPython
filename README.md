## GeoPython
### Introduction to read, write and manipulate and visualize  spatial data using python

### Geometric Objects & Spatial Analysis in Python

1. Core Geometric Objects (Shapely)
  - Point: Single (x,y) or (x,y,z) location
  - LineString: Connected points (min 2 coordinates)
  - Polygon: Filled area with exterior ring + optional holes
  - Multi- variants: Collections of points/lines/polygons

2. Geopandas Essentials
  - Read/write spatial data (Shapefiles, GeoJSON)
  - Combine Pandas tabular operations with spatial functions
  - CRS management and transformations

3. Key Spatial Operations
  - Geocoding: Address ↔ Coordinates (geopy)
  - Projections: CRS detection/reprojection
  - Spatial Joins: Point-in-polygon, layer combinations

4. Advanced Analysis
  - Reclassification:
    - Custom rules (e.g., lake size: big/small via mean)
    - Pre-built classifiers (pysal)
  - Overlay Analysis: Filter features by boundaries

5. Mapping Tools
- Bokeh Workflow:
  - Load data → GeoDataFrame
  - Extract x/y coordinates
  - Convert to Bokeh DataSource
  - Plot as circles (points), lines, or patches (polygons)
