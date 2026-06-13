ASU Heat Safety Dashboard

A responsive web dashboard that monitors weather and heat-related conditions for four Arizona State University campuses using data from the National Weather Service (NWS).

Overview

This dashboard provides near real-time weather conditions and heat-related alerts for:

* ASU West
* ASU Downtown Phoenix
* ASU Tempe
* ASU Polytechnic

The page automatically retrieves data from the National Weather Service API whenever the page is loaded or refreshed and presents the information in an easy-to-read visual format.

Features

Weather Data

For each campus, the dashboard displays:

* Campus name
* Latitude and longitude
* Current temperature
* Relative humidity
* Wind speed
* Wind direction
* Current weather conditions
* Active weather advisories
* Last refresh time

Heat Safety Status Indicators

The dashboard uses a simple visual status system:

Status	Color	Meaning
Normal	Green	No active heat concerns
Advisory	Yellow	Heat Advisory or elevated heat conditions
Warning	Red	Extreme Heat Warning or severe heat conditions

Responsive Design

The dashboard automatically adjusts based on screen size:

Desktop / Large Displays

* Four campus panels displayed side-by-side
* Optimized for safety operations centers and office monitors

Tablets

* Two-column layout

Mobile Devices

* Single-column stacked layout
* Optimized for phones and field supervisors

Data Sources

Weather data is provided by the National Weather Service (NWS):

* https://api.weather.gov

The dashboard retrieves:

* Current observations
* Temperature
* Humidity
* Wind information
* Active weather alerts
* Heat advisories
* Extreme heat warnings

Campus Locations

Campus	Latitude	Longitude
ASU West	33.6079039	-112.1609696
ASU Downtown	33.4539316	-112.0705604
ASU Tempe	33.4210000	-111.9340000
ASU Polytechnic	33.3061605	-111.6791023

Color Palette

This dashboard uses Arizona State University brand colors:

Color	Hex
ASU Maroon	#8C1D40
ASU Gold	#FFC627
ASU Rich Black	#000000
ASU White	#FFFFFF

Deployment

GitHub Pages

1. Create a GitHub repository.
2. Upload:
    * index.html
    * README.md
3. Enable GitHub Pages.
4. Select:
    * Deploy from branch
    * Main branch
    * Root folder
5. Save.

The dashboard will become available at:

https://YOUR-GITHUB-USERNAME.github.io/REPOSITORY-NAME/

Refreshing Data

Weather data is retrieved each time the page is loaded or refreshed.

Users can refresh the browser at any time to retrieve the latest NWS conditions and alerts.

The dashboard displays the last update time so users can verify data freshness.

Future Enhancements

Potential enhancements include:

* Automatic refresh every 5–15 minutes
* Heat Index calculations
* Wet Bulb Globe Temperature (WBGT) calculations
* Email notifications
* SMS alerts
* Microsoft Teams integration
* Historical weather trends
* Work restriction recommendations
* Exportable daily reports
* Additional ASU campuses and facilities

Disclaimer

This dashboard is intended as an operational awareness tool.

Users should continue to follow all Arizona State University environmental health and safety policies, procedures, and guidance when making decisions regarding outdoor work activities.

Weather data and alerts are provided by the National Weather Service and may be subject to delays, updates, or revisions.
