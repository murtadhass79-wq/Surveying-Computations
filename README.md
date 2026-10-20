# Surveying Forward and Inverse Computations

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
