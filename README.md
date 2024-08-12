# NASA-OCO2-File-Conversion

NASA's OCO-2 Satellite data is stored in NetCDF4 (HDF) files, which aren't readable in QGIS (geographic information system software used by NASA). This Python script converts the data in the NetCDF4 files into CSV format. The script extracts and processes data related to atmospheric CO2 levels, including geographical and temporal information, and outputs the cleaned data into a CSV file for further analysis in QGIS. 

# Features
Data Extraction: Reads CO2 concentration data, latitude, longitude, and quality flags from NetCDF4 files.
Date Conversion: Converts date-time information from NetCDF4 format to a pandas-friendly format.
Data Cleaning: Filters out data points based on quality flags.
CSV Export: Saves the cleaned and processed data into a CSV file named based on the date extracted from the dataset.
