1# Surveying Forward and Inverse Computations

A small teaching repository for surveying students. It demonstrates using GitHub and Google Colab to run surveying calculations.

## Contents
- `Surveying_Forward_Inverse_Computations.ipynb`: interactive notebook.
- Forward computation: calculate point 2 from point 1, distance, and azimuth.
- Inverse computation: calculate distance and azimuth between two known points.
- Interactive prompts ask the user which calculation to perform and request the required inputs.

## Open in Google Colab
After uploading this repository to GitHub, use this URL pattern:

`https://colab.research.google.com/github/YOUR-USERNAME/YOUR-REPOSITORY/blob/main/Surveying_Forward_Inverse_Computations.ipynb`

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with your GitHub username and repository name.

## Coordinate convention
- Coordinates are Easting (E) and Northing (N).
- Azimuth is measured clockwise from North.
- Use consistent units for coordinates and distance (for example, metres).
- This is a plane-coordinate calculation; it does not perform geodetic or map-projection transformations.

## Suggested student workflow
1. Open the notebook from GitHub in Google Colab.
2. Run the first code cell to define the functions.
3. Run the calculator cell and choose Forward or Inverse.
4. Enter the requested coordinates, distance, and/or azimuth.
-----------------------------------------------------------------------------

2 # Consecutive Point Distance Calculator

Google Colab notebook for calculating horizontal distances between consecutive surveying points.

## Input format
The supplied example `Survey_Points.txt` is comma-separated and contains these columns:

- `P`: point identifier
- `N`: Northing
- `E`: Easting
- `Z`: elevation (retained but not used for horizontal distance)

## How to use
1. Upload `Consecutive_Point_Distances.ipynb` to GitHub or open it in Google Colab.
2. Put `Survey_Points.txt` (or your similarly structured CSV file) in Google Drive.
3. Run the Drive connection cell and authorize access.
4. Edit `file_path` to match the file's location in `MyDrive`.
5. Run all cells in order.
6. Download `Consecutive_Point_Distances.csv`.

Points are processed in their original row order. Coordinates must be projected Easting/Northing in the same linear unit. Latitude/longitude in degrees require a geodesic method instead.

