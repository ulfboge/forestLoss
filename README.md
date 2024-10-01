# Forest Loss Analysis: RADD Alerts and Hansen Global Forest Change

This repository contains all the necessary files and code to reproduce the forest loss analysis for [specify the region or area]. The repository includes rasters derived from RADD alerts and Hansen Global Forest Change data, as well as the script used in Google Earth Engine (GEE) to generate the results.

## Repository Contents

- **/rasters/**
  - `radd_forest_loss.tif`: Raster file representing forest loss detected by RADD alerts for the year [specify year].
  - `hansen_forest_loss.tif`: Raster file representing forest loss from the Hansen Global Forest Change dataset for the same year.
  
- **/area_file/**
  - `area_of_interest.shp`: Shapefile containing the boundaries of the area used in this analysis.

- **GEE Script**
  - `forest_loss_analysis.js`: Google Earth Engine script that processes the forest loss data using the RADD alerts and Hansen datasets, filtering by time and region.

## How to Use

1. **Google Earth Engine (GEE) Setup**
   - The analysis can be replicated by using the provided GEE script (`forest_loss_analysis.js`). Make sure you have access to a Google Earth Engine account.
   - Copy the script into your GEE code editor, adjust the area of interest if needed, and run the analysis.
   
2. **Data**
   - The raster files can be downloaded directly from the `/rasters` directory and visualized in any GIS software such as QGIS or ArcGIS.
   
3. **Analysis**
   - The script processes RADD alerts and Hansen data over the same time period to derive forest loss maps, allowing for a comparative analysis of near real-time deforestation alerts vs. annual forest loss measurements.
   
## Dependencies

- Google Earth Engine account.
- GIS software for visualizing the raster files (QGIS, ArcGIS, etc.).
- Earth Engine datasets: 
  - RADD alerts
  - Hansen Global Forest Change (version 2024)
  
## License

This project is licensed under the [Your License Here].

## Contributions

Feel free to fork this repository and make pull requests for improvements or further analysis. Any feedback or suggestions are welcome!

## Contact

For any inquiries or further information, contact Johan Karlsson at johan@kombagis.se.
