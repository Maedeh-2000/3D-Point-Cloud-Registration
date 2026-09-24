# 3D Point Cloud Registration & Quality Assessment

A geomatics and computer vision project focused on the registration, accuracy assessment, and visualization of terrestrial photogrammetry and airborne laser scanning (ALS) point clouds.

The project demonstrates a complete workflow from point cloud preparation and registration to geometric quality assessment and 3D visualization.

## Project Overview

The objective of this project was to integrate terrestrial photogrammetry and ALS point clouds of a building into a common coordinate system and evaluate the geometric quality of the resulting data.

The workflow included:

- Preparation of terrestrial photogrammetry and ALS point clouds
- Point cloud registration using Ground Control Points (GCPs)
- Accuracy assessment using GCPs and independent check points
- Geometric quality analysis of the terrestrial point cloud
- Integration and visualization of the registered datasets
- 3D visualization using Cesium

## Data

### Terrestrial Photogrammetry Point Cloud

- Approximately **18 million points**
- Coordinate system: **ETRS89 / UTM Zone 32N**
- Height reference: **DHHN2016**
- High level of façade detail

Some limitations included uneven point density, small gaps in roof areas due to limited viewing angles, and noise around edges and fine architectural details.

### Airborne Laser Scanning (ALS)

- Approximately **37,000 points** after cropping to the study area
- Coordinate system: **ETRS89 / UTM Zone 32N**
- Height reference: **DHHN2016**
- Used as the reference dataset for registration and GCP extraction

## Point Cloud Registration

A coarse alignment was performed using selected Ground Control Points.

The terrestrial photogrammetry and ALS point clouds were subsequently registered and merged using **CloudCompare**.

**Final RMS alignment error: 154 mm**

A scale check was also performed to verify consistency between the datasets.

## Accuracy Assessment

Ground Control Points and independent check points were used to evaluate registration accuracy.

- GCP errors: **0.034 m – 0.153 m**
- Check point errors: **0.229 m – 0.590 m**
- Most GCPs achieved sub-20 cm accuracy

Higher errors were mainly associated with points affected by limited visibility or steep observation angles.

## Geometric Quality Assessment

The geometric quality of the terrestrial point cloud was evaluated by fitting a plane to a planar façade section.

**RMS deviation: 0.06 m**

The result indicates a relatively low noise level and good local surface consistency.

## 3D Visualization

The processed point cloud was also prepared for interactive 3D visualization using **Cesium**.

This allows the spatial dataset to be explored in a web-based 3D environment and provides an intuitive representation of the registered point cloud.

## Tools & Technologies

- CloudCompare
- Cesium
- Terrestrial Photogrammetry
- Airborne Laser Scanning (ALS)
- Point Cloud Processing
- Ground Control Points (GCPs)
- Geometric Accuracy Assessment
- ETRS89 / UTM Zone 32N

## Key Skills Demonstrated

- 3D geospatial data processing
- Point cloud registration
- Coordinate reference systems
- Accuracy and error analysis
- Geometric quality assessment
- Integration of heterogeneous geospatial datasets
- 3D geospatial visualization

## Results

The project successfully integrated terrestrial photogrammetry and ALS point clouds into a common spatial reference. Registration accuracy and local geometric quality were quantitatively evaluated using control points, check points, and planar surface analysis.

---

**Maedeh Jebelli**  
M.Sc. Geomatics Engineering — University of Stuttgart
