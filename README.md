Climate Data Extraction Tool
This tool extracts climate data from .nc files based on specified latitude and longitude coordinates and exports the data to .xls format. It is designed to work with datasets like those from the World Bank Knowledge Portal's CMIP6 Climate Datasets.

Data Source Provider: World Bank Knowledge Portal
Dataset: CMIP6 Climate Datasets
Input Format: .nc (NetCDF)
Output Format: .xls (Excel)
Prerequisites
Python 3.7 or higher
Required Python libraries: netCDF4, pandas, numpy, openpyxl

**Usage Instructions**
**Prepare Your Data:**
Download .nc files from the World Bank Knowledge Portal.
Place all .nc files in a single folder.

**Run the Script:**
Modify the folder_path, latitude, longitude, and output_folder variables in the script to match your input data folder, desired coordinates, and output location.
Execute the script to extract data for the given latitude and longitude and save the results in separate .xls files.
**Output:**
Extracted data will be saved as .xls files in the specified output folder. Each file corresponds to one .nc fil
