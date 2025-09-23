# 2024-AL-Precinct-Locations

**Disclaimer:** This repository is not an official source of Alabama precinct information. Users should exercise discretion and refer to official data released by Alabama counties for accurate and up-to-date precinct details.

I'm collaborating with the [Alabama Progress Discord server](https://discord.gg/t7b5ryw5NG) on a political research project to provide statewide latitude and longitude coordinates for Alabama precincts. We're geocoding addresses sourced from each county and using the labels from the [2024 General Election Results - Precinct Level](https://www.sos.alabama.gov/alabama-votes/voter/election-data) dataset on the Alabama Secretary of State's website. The result is a set of spreadsheets containing precinct names, addresses, and their corresponding geographic coordinates.

# Geocoding Methods

Geographic coordinates were generated using a mix of:
* [Nominatim](https://nominatim.org/) (OpenStreetMap-based geocoding)
* [Google Maps](https://developers.google.com/maps/documentation/geocoding/overview) (used only when open-source data was insufficient or incomplete)

# County Datasets

Each output county spreadsheet includes:

* Precinct name
* Precinct address
* Latitude and longitude coordinates

Volunteers from the Discord server have contributed to compiling data for many counties so far. The result is a growing set of spreadsheets that aim to improve accessibility and transparency around precinct locations in Alabama and to assist political researchers with useful geospatial datasets. If you’d like to contribute to this project, please reach out to us on the Alabama Progress Discord Server. If you find an issue with any dataset, please [open an issue](https://github.com/Corey4005/2024-AL-Precinct-Locations/issues). 


| County            | FIPS Code | Done? | Discord Contributor | 
| ----------------- | --------- | ----- | ------------------- | 
| Autauga County    | 001       | Yes   | butterbeancw        |
| Baldwin County    | 003       |       |                     |
| Barbour County    | 005       |       |                     |
| Bibb County       | 007       |       |                     |
| Blount County     | 009       |       |                     |
| Bullock County    | 011       |       |                     |
| Butler County     | 013       |       |                     |
| Calhoun County    | 015       |       |                     |
| Chambers County   | 017       |       |                     |
| Cherokee County   | 019       |       |                     |
| Chilton County    | 021       |       |                     |
| Choctaw County    | 023       |       |                     |
| Clarke County     | 025       |       |                     |
| Clay County       | 027       |       |                     |
| Cleburne County   | 029       |       |                     |
| Coffee County     | 031       |       |                     |
| Colbert County    | 033       |       |                     |
| Conecuh County    | 035       |       |                     |
| Coosa County      | 037       |       |                     |
| Covington County  | 039       |       |                     |
| Crenshaw County   | 041       |       |                     |
| Cullman County    | 043       | Yes   | squigglejot         |
| Dale County       | 045       |       |                     |
| Dallas County     | 047       |       |                     |
| DeKalb County     | 049       |       |                     |
| Elmore County     | 051       |       |                     |
| Escambia County   | 053       |       |                     |
| Etowah County     | 055       |       |                     |
| Fayette County    | 057       |       |                     |
| Franklin County   | 059       |       |                     |
| Geneva County     | 061       |       |                     |
| Greene County     | 063       |       |                     |
| Hale County       | 065       |       |                     |
| Henry County      | 067       |       |                     |
| Houston County    | 069       |       |                     |
| Jackson County    | 071       |       |                     |
| Jefferson County  | 073       |       |                     |
| Lamar County      | 075       |       |                     |
| Lauderdale County | 077       |       |                     |
| Lawrence County   | 079       |       |                     |
| Lee County        | 081       |       |                     |
| Limestone County  | 083       |       |                     |
| Lowndes County    | 085       |       |                     |
| Macon County      | 087       |       |                     |
| Madison County    | 089       | Yes   | BamaProgress        |
| Marengo County    | 091       |       |                     |
| Marion County     | 093       |       |                     |
| Marshall County   | 095       |       |                     |
| Mobile County     | 097       |       |                     |
| Monroe County     | 099       |       |                     |
| Montgomery County | 101       |       |                     |
| Morgan County     | 103       |       |                     |
| Perry County      | 105       |       |                     |
| Pickens County    | 107       |       |                     |
| Pike County       | 109       |       |                     |
| Randolph County   | 111       |       |                     |
| Russell County    | 113       |       |                     |
| St. Clair County  | 115       |       |                     |
| Shelby County     | 117       |       |                     |
| Sumter County     | 119       |       |                     |
| Talladega County  | 121       |       |                     |
| Tallapoosa County | 123       |       |                     |
| Tuscaloosa County | 125       |       |                     |
| Walker County     | 127       |       |                     |
| Washington County | 129       |       |                     |
| Wilcox County     | 131       |       |                     |
| Winston County    | 133       |       |                     |
