### Identifiers

| Relationship   | ID Type             | ID(s)                                                                                                                                                                                                                                                                    |
|:---------------|:--------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| root           | osuked_id           | 10169                                                                                                                                                                                                                                                                    |
| element-of     | sett_bmu_id         | E_BURBO                                                                                                                                                                                                                                                                  |
| element-of     | ngc_bmu_id          | BURBW-1                                                                                                                                                                                                                                                                  |
| element-of     | 4c_offshore_id      | [burbo-bank-united-kingdom-uk02](https://www.4coffshore.com/windfarms/united-kingdom/burbo-bank-united-kingdom-uk02.html), [burbo-bank-extension-united-kingdom-uk59](https://www.4coffshore.com/windfarms/united-kingdom/burbo-bank-extension-united-kingdom-uk59.html) |
| element-of     | power_technology_id | [burbowind](https://www.power-technology.com/projects/burbowind), [burbo-bank-extension-offshore-wind-farm-liverpool-bay](https://www.power-technology.com/projects/burbo-bank-extension-offshore-wind-farm-liverpool-bay)                                               |
| same-as        | gppd_idnr           | GBR0002487                                                                                                                                                                                                                                                               |
| same-as        | esail_id            | BURBO                                                                                                                                                                                                                                                                    |
| same-as        | name                | Burbo Bank Offshore Windfarm                                                                                                                                                                                                                                             |
| same-as        | windpowernet_id     | windfarm_en_10684_burbo-bank                                                                                                                                                                                                                                             |
| same-as        | wikidata_id         | Q2583856                                                                                                                                                                                                                                                                 |
| same-as        | wikipedia_id        | Burbo_Bank_Offshore_Wind_Farm                                                                                                                                                                                                                                            |

<br>
### Datasets
##### <a href="https://raw.githubusercontent.com/OSUKED/Dictionary-Datasets/main/datasets/plant-locations/datapackage.json">Plant Locations</a>

Dataset listing the locations of power plants

The "osuked_id" field was used to match from the dictionary to the "osuked_id" field in this dataset.

| Attribute   |   Value |
|:------------|--------:|
| Longitude   |   -3.20 |
| Latitude    |   53.49 |

<br><br>
##### <a href="https://raw.githubusercontent.com/OSUKED/Dictionary-Datasets/main/datasets/wind-farms/datapackage.json">Wind Farms</a>

Dataset listing the plant types and hub-heights of wind farms

The "osuked_id" field was used to match from the dictionary to the "osuked_id" field in this dataset.

| Attribute   | Value    |
|:------------|:---------|
| Plant Type  | offshore |
| Hub-Height  | 88.0     |

<br><br>
##### <a href="https://raw.githubusercontent.com/OSUKED/Dictionary-Datasets/main/datasets/global-power-plant-database/datapackage.json">Global Power Plant Database</a>

The Global Power Plant Database is a comprehensive, open source database of power plants around the world. It centralizes power plant data to make it easier to navigate, compare and draw insights for one’s own analysis. The database covers approximately 35,000 power plants from 167 countries and includes thermal plants (e.g. coal, gas, oil, nuclear, biomass, waste, geothermal) and renewables (e.g. hydro, wind, solar). Each power plant is geolocated and entries contain information on plant capacity, generation, ownership, and fuel type. It will be continuously updated as data becomes available. 

The methodology for the dataset creation is given in the World Resources Institute publication ["A Global Database of Power Plants"](https://www.wri.org/research/global-database-power-plants). Data updates may occur without associated updates to this manuscript.

The "gppd_idnr" field was used to match from the dictionary to the "gppd_idnr" field in this dataset.

| Attribute                           | Value                                                                    |
|:------------------------------------|:-------------------------------------------------------------------------|
| Installed Capacity (MW)             | 90.0                                                                     |
| Longitude                           | -3.1849                                                                  |
| Latitude                            | 53.4882                                                                  |
| Primary Fuel Type                   | Wind                                                                     |
| Owner                               | Orsted (formerly Dong Energy)                                            |
| Source                              | UK Renewable Energy Planning Database                                    |
| URL                                 | https://www.gov.uk/government/collections/renewable-energy-planning-data |
| Geolocation Source                  | UK Renewable Energy Planning Database                                    |
| PLATTS-WEPP ID                      | 1061638.0                                                                |
| Estimated Annual Generation in 2017 | 226.88                                                                   |

<br><br>
##### <a href="https://raw.githubusercontent.com/OSUKED/Dictionary-Datasets/main/datasets/annual-output/datapackage.json">Annual Output</a>

Total annual production of individual transmission level power plants on the GB power system

The "ngc_bmu_id" field was used to match from the dictionary to the "ngc_bmu_id" field in this dataset.

| Attribute           |   Year |     Value |
|:--------------------|-------:|----------:|
| Annual Output (MWh) |   2016 | 253554.18 |
| Annual Output (MWh) |   2017 | 214792.00 |
| Annual Output (MWh) |   2018 | 258506.21 |
| Annual Output (MWh) |   2019 | 244645.98 |
| Annual Output (MWh) |   2020 | 296631.67 |

<br><br>
##### <a href="https://raw.githubusercontent.com/OSUKED/Dictionary-Datasets/main/datasets/bmu-fuel-types/datapackage.json">Bmu Fuel Types</a>

Dataset published by Elexon describing the fuel types of the Balancing Mechanism Units (BMUs) that they process market settlement for. This dataset was retrieved from Elexon at 2021-08-09

The "ngc_bmu_id" field was used to match from the dictionary to the "NGC_BMU_ID" field in this dataset.

| Attribute   | Value   |
|:------------|:--------|
| Fuel Type   | WIND    |
