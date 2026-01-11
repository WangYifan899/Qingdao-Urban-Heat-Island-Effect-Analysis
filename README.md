# qingdao-urban-heat-island-analysis-tool
This is an interactive urban heat island (UHI) analysis system developed on Google Earth Engine (GEE), specifically designed for Qingdao. The system integrates multi-source remote sensing data to automate UHI calculation, visualization, and data export
## Key Features
- Integrates Landsat 8 and Sentinel-2 data to automatically calculate land surface temperature, NDVI, NDBI, and UHI classification levels
- Supports exporting UHI maps in GeoTIFF format and zonal statistical data in CSV format
- Multi-layer display including UHI classification maps, land surface temperature maps, vegetation index maps, etc
- User-friendly web interface allows complex analysis with simple clicks
## How to Use
1. Access the application link:
   - https://xenon-crossbar-483711-h3.projects.earthengine.app/view/qingdao-urban-heat-island-analysis-tool
2. Click the "Run UHI Analysis" button, the system will automatically
3. Click the "LST" "NBVI" "NDVI"buttons to display temperature,vegetabtion,and built—up layers
4. After analysis completion, click the corresponding buttons to downloadClick the corresponding export buttons to download the GeoTIFF image or CSV statistical results
## Technical Dependencies
- Google Earth Engine (GEE): Core computing platform
- JavaScript GEE API: Development language
- Remote Sensing Data:Landsat 8 Collection 2 Tier 1 and Sentinel-2 MSI Level-2A
- GIS Tools: QGIS, ArcGIS, etc. for subsequent data analysis
## Code Access
GEE Script Link:
- https://code.earthengine.google.com/96375b9e1cf4e9e0f775b64f4361a7c2
