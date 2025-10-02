# Human_Elephant_Conflict_in_Gudalur

# Project Title: Human-Elephant Conflict (HEC) Hotspot and Vulnerability Analysis in Gudalur Forest Division, Tamil Nadu 
This project uses Geographic Information Systems (GIS) to identify and analyze hotspots of Human-Elephant Conflict (HEC) and assess human vulnerability in the Gudalur Forest Division of Tamil Nadu. The goal is to provide a spatial understanding of the conflict to inform more targeted and effective conservation and policy interventions.

Key Findings & Visualizations
Key Findings and Maps
Conflict Hotspot Analysis: The analysis identifies specific areas with a high concentration of reported HEC incidents, revealing patterns that can be linked to habitat fragmentation and human settlements.

Vulnerability Mapping: The project maps areas of high human vulnerability based on proximity to conflict zones and population density, highlighting communities most at risk.

Vulnerability-Risk Overlay: The final maps overlay conflict hotspots with human vulnerability, pinpointing the critical zones where intervention is most urgently needed.


Conflict Hotspot Map: <img width="3507" height="2480" alt="Gudalur HEC Map" src="https://github.com/user-attachments/assets/cbf9bf82-355c-45ba-ab67-4fb19a29ddbd" />


Vulnerability Analysis Map: <img width="931" height="757" alt="Gudalur_Vulnerability_Map" src="https://github.com/user-attachments/assets/99d8b19f-4cdc-4a91-be58-8874db388284" />

Methodology & Tools
Spatial Analysis: I used QGIS to process and analyze geographical data layers including elephant habitats, land use patterns, and human population density.

Data Sources: 
1.	Administrative Boundaries: Administrative boundaries for Tamil Nadu and its districts were sourced from the Humanitarian Data Exchange (HDX).
2. Protected Areas: The boundaries for Bandipur, Mudumalai National Parks were available on OSM and Wayanad Wildlife Sanctuary was meticulously traced using OpenStreetMap (OSM) as a base layer.
3. Landscape and Human Features: Key landscape features, including roads, rivers, and human settlements, were obtained from OpenStreetMap (OSM) to provide a comprehensive view of the human footprint in the region.
4. Land Use/Land Cover (LULC): The Esri Land Cover dataset was utilized to understand the different types of land use (e.g., forests, agriculture, urban areas) across the study area.
5. Conflict Data: Conflict data points were manually generated based on a vulnerability analysis that incorporated ecological reasoning, allowing for the creation of a realistic and ecologically-informed conflict dataset.

Tools and Analysis
All data processing, geospatial analysis, and mapping were performed using QGIS. 
Key analytical techniques included:
1.	Data Preparation: Sourcing, cleaning, and re-projecting all spatial data layers to ensure a consistent coordinate system.
2. Kernel Density Estimation (KDE): This statistical method was applied to the conflict data points to identify and visualize high-density "hotspot" areas.
3. Proximity Analysis: We analyzed the proximity of human settlements and roads to both conflict hotspots and elephant habitats to assess the level of human vulnerability.
4. Spatial Overlay: Multiple layers (e.g., LULC, hotspots, and human settlements) were overlaid to pinpoint the specific areas where human activity and elephant movement are most likely to result in conflict.

How to Use This Project
You can replicate or build upon this analysis by following the steps below.
Clone the Repository: Download all the project files from this GitHub repository.
Open in QGIS: Open the .qgz project file in QGIS to view all the layers, symbology, and analysis outputs.
Explore the Data: You can explore the data layers, modify the symbology, or perform further analysis using the provided data files.
