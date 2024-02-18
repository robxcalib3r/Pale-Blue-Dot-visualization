# Pale Blue Dot Competition
## Criteria
create a visualisation using Earth observation data that advances at least one of the following -
1. Zero Hunger
2. Clean water and sanitation
3. Climate action
must use at least one publicly available Earth observation dataset collected by a U.S. government agency.
"Earth observation data" means observations about the Earth collected in space, such as satellite data, airborne, and in-situ sensors.


## Problem Formulation
Based on the 3 criteria, formulating a combined problem is kind of tough. 

1. Showing visualisation of natural disasters that affected the clean water and sanitation services ultimately hampering the crop yields
2. example can be frequency of floods that are destroying clean water sources and crops
  - Historical data of floods
  - How it is affecting water sources
  - Water Quality checking parameters - [1]
    - chlorophyll-a, 
        - Works best within 675-700 nm
    - turbidity and Total Suspended Solids (TSS),
        - Red and NIR bands are found to be useful
        - Multiple band reflectance ratios > reduce atmospheric effect + increase Signal-Noise ratio
    - Secchi Disk Depth (SDD), and
        - Inversely related to turbidity
        - Estimated using empirical relationships with turbidity
    - Colored Dissolved Organic Matter (CDOM), 
        - Strongly correlated to Chl-a, TSS and Turbidity levels
  - Water Quantity
        - Water levels
            - Satellite altimetric datasets
              - Jason -2, 3
              - Saral
  - Crop yields in those areas
3. Another example can be desertification which increases the surface temperature of lands and water bodies, decreasing the soil moisture and water amount in lakes, ponds and we can show a visualisation of that affecting vegetation and fish population.
  - Desertification
    - Normalised Difference Vegetation Index (NDVI) (< 0.2)
    - Net Primary Production (NPP)
    - Precipitation
    - Vegetation Coverage and type
      - Severe < 5%
      - High 5-20%
      - Moderate 21-50%
      - Slight 51-70%
      - Non desertification > 70%
    - Land use and Land Cover (LULC)
  - Same as previous water quality and quantity checking parameters for water reservoirs
  - Need ground based data for vegetation and crop production (NPP)
  - Need ground based data for fish population
4. Visualising crop and vegetation production (Food sources) due to sea level rise (climate change > Temp increase > decrease in ice of himalayas or others > water runoff > sea level rise > Salinization increase > land decrease)
5. Visualise the effects of climate change on ecosystems, including shifts in vegetation, biodiversity loss, and disruptions to animal habitats. Use interactive maps to show how these changes affect specific species and their migration patterns.
