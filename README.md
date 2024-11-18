# Ikeja-Healthcare-new-site
This map shows the land location within the local government of Ikeja that is advisable for have a new healthcare center after considering factors like land use, accessibility to major roads, population density and distance from existing healthcare centers within the region. This project assesses healthcare suitability within Ikeja Local Government Area (LGA), based on factors like road infrastructure, healthcare facilities, population density, and land use. A weighted scoring system is used to evaluate each region's healthcare access, with results displayed on a color-coded map to visually represent the suitability levels for healthcare provision.

### Color-Coding Map Legend

- **Blue**: Not Suitable for healthcare access.
- **Light Cyan**: Fairly Suitable for healthcare access.
- **Yellow**: Suitable for healthcare access.
- **Red**: Most Suitable for healthcare access.

## Data Sources

The analysis uses the following datasets:

- **Road Infrastructure**: Data on the quality and proximity of roads to healthcare facilities.
- **Healthcare Facilities**: The distribution of healthcare services such as hospitals, clinics, and health centers.
- **Population Density**: The number of people per square kilometer to gauge healthcare demand.
- **Land Use**: Classification of land use (e.g., residential, commercial, industrial) to assess accessibility to healthcare.

## Methodology

### Weighted Scoring Model

Each factor is assigned a weight based on its importance in determining healthcare suitability:

- **Road Infrastructure**: 20% of the total score
- **Healthcare Facilities**: 40% of the total score
- **Population Density**: 20% of the total score
- **Land Use**: 20% of the total score

Regions are scored on a scale from 1 to 5 for each factor. The weighted sum of these scores determines the overall healthcare suitability score for each region.

### Color-Coding Scheme

Once the suitability scores are calculated, regions are categorized as follows:

- **Blue (Not Suitable)**: Score between 1.0 - 2.0
- **Light Cyan (Fairly Suitable)**: Score between 2.1 - 3.0
- **Yellow (Suitable)**: Score between 3.1 - 4.0
- **Red (Most Suitable)**: Score between 4.1 - 5.0

This color-coding is applied to the map, allowing easy visualization of areas most and least suitable for healthcare access.
