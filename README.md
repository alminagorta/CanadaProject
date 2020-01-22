# Canada Project
[biological, chemical, habitat data]: https://github.com/alminagorta/CanadaProject/tree/master/Benthic_Habitat_Data
[fish data available]: https://github.com/alminagorta/CanadaProject/tree/master/FishData

This repository contains data collection and data analysis in Canada. Biological, chemical, hydrological, and spatial data were collected for multiple provinces in Canada. The map below presents the sites where data are available. Red dots are sites with [biological, chemical, habitat data], while blue dots are sites with [fish data available].

 ![](https://github.com/alminagorta/CanadaProject/blob/master/Miscel/All_CABIN_Ianfish_OBBN.png)

You can find the interactive map at https://bit.ly/2XBBkDO 

[BSD 3-Clause license]: https://github.com/alminagorta/CanadaProject/blob/master/Miscel/LICENSE
[EcoCat copyright]: https://www2.gov.bc.ca/gov/content/home/copyright
[CABIN license]: https://open.canada.ca/en/open-government-licence-canada

[Ecological Reports Catalogue of British Columbia]: https://github.com/alminagorta/CanadaProject/tree/master/FishData#ecocat-bc-ecological-reports-catalogue-of-british-columbia
[EcoCat BC]: http://a100.gov.bc.ca/pub/acat/public/welcome.do 

[the Canadian Aquatic Biomonitoring Network]: https://github.com/alminagorta/CanadaProject/tree/master/Benthic_Habitat_Data#cabin-canadian-aquatic-biomonitoring-network
[Ontario Benthos Biomonitoring Network]: https://github.com/alminagorta/CanadaProject/tree/master/Benthic_Habitat_Data#obbn-ontario-benthos-biomonitoring-network

[Alberta_Lake]: http://albertalakes.ualberta.ca/?page=lake
[BC_Lake]: http://a100.gov.bc.ca/pub/fidq/searchBathymetricMaps.do

[cluster analysis]: https://github.com/alminagorta/MachineLearning/tree/master/Clustering

[St. Lawrence Drainage Area]: https://github.com/alminagorta/CanadaProject/blob/master/Benthic_Habitat_Data/2_St_Lawrence_BenthicData.csv
[python code]: https://github.com/alminagorta/CanadaProject/tree/master/Python_Code
[Fig1]: https://github.com/alminagorta/CanadaProject/blob/master/Benthic_Habitat_Data/Benthic_2.png 
[Ontario Freshwater Fishes Life History Database]: http://www.ontariofishes.ca/home.htm
[OBBN]: https://data.ontario.ca/dataset/ontario-benthos-biomonitoring-network
[Ontario Ministry of Natural Resources & Forestry]: https://github.com/alminagorta/CanadaProject/tree/master/FishData#omnrf-ontario-ministry-of-natural-resources--forestry


[Benthic and habitat data]: https://github.com/alminagorta/CanadaProject/tree/master/Benthic_Habitat_Data
[Fish data]: https://github.com/alminagorta/CanadaProject/tree/master/FishData

## Data Source:
To find the raw data:
* [Benthic and habitat data] come from:
  * [the Canadian Aquatic Biomonitoring Network] (CABIN) and 
  * the [Ontario Benthos Biomonitoring Network] => ([OBBN]). 
* [Fish data] come from:
  * [Ecological Reports Catalogue of British Columbia] =>  ([EcoCat BC]) 
  * [Ontario Ministry of Natural Resources & Forestry] (only electrofishing data-efish)
  * [Ontario Freshwater Fishes Life History Database] 
  
   
## Data Analysis:
### Benthic Data
An example of the benthic data at [St. Lawrence Drainage Area] (from CABIN data) was processed using a [python code]. Some results of the class of invertebrates and type of data available per site are presented below 

<img src="https://github.com/alminagorta/CanadaProject/blob/master/Miscel/Benthic_2.png" width=200/><img src="https://github.com/alminagorta/CanadaProject/blob/master/Miscel/Out2_St_Lawrence_Drainage%20AreaDataAva_2.png" width=200/><img src="https://github.com/alminagorta/CanadaProject/blob/master/Miscel/OutAll_DrainageAreasmap_A.png" width=350/>

### Fish Data
Fish data parameters (e.g., lenght, weight, age) from the [Ontario Freshwater Fishes Life History Database] are presented in this [interactive table]. Also a [cluster analysis] was implemented based on spawning temperature. 


<img src="https://github.com/alminagorta/CanadaProject/blob/master/Miscel/Table1.png" width=280/><img src="https://github.com/alminagorta/MachineLearning/blob/master/Clustering/K-means.png" width=280/><img src="https://github.com/alminagorta/MachineLearning/blob/master/Clustering/Dendogram1.png" width=280/>


[interactive table]: http://oalminagorta.byethost7.com/Table_FishOntario/Table3_FishOntario.html 

## Additional Resources: 
* Lakes-Specific Provinces
  * Basic lake data such as area, max depth, elevation in Alberta and BC see => [Alberta_Lake] or [BC_Lake] 
  * 444 inland lakes in Ontario: Lake characteristics, fish, water quality parameters, and zebra mussel cases==> see: Broad-scale Monitoring program (contact: Ontario Ministry of Natural Resources and Forestry)=> [Data description BsM]
  
[Data description BsM]: https://github.com/alminagorta/CanadaProject/blob/master/FishData/BsM_DataDescriptions.pdf
  

[National Hydro Network]: https://open.canada.ca/data/en/dataset/a4b190fe-e090-4e6d-881e-b87956c07977
[Geospatial Product index]: http://ftp.geogratis.gc.ca/pub/nrcan_rncan/vector/index/html/geospatial_product_index_en.html

* Spatial Information - All Canada
  * [National Hydro Network]: Multiple formats (e.g., shp,KMZ)
  * [Geospatial Product index]: To download very specific working unit
* Others
  * [Ontario Data]
  * [Ice thickness] 
  * [Website of the project] (In progress)
  * [River Community Benchmarks] (Randall et.al 2017)
  * [100 yrs Water Levels - Great Lakes ]
  * [Fisheries and wildlife] inventory data in Alberta (spatially access)



[River Community Benchmarks]: http://waves-vagues.dfo-mpo.gc.ca/Library/40603520.pdf
[Ice thickness]: https://www.canada.ca/en/environment-climate-change/services/ice-forecasts-observations/latest-conditions/archive-overview/thickness-data.html
[Ontario Data]: https://data.ontario.ca/
[100 yrs Water Levels - Great Lakes ]: http://www.tides.gc.ca/C&A/network_means-eng.html#tabs1_5
[Fisheries and wildlife]: https://maps.alberta.ca/FWIMT_Pub/Viewer/?TermsOfUseRequired=true&Viewer=FWIMT_Pub
  
## Licensing:
* For the benthic and habitat data, see [CABIN license] and OBBN license.
* For the fish data in EcoCat see [EcoCat copyright]
* For the [Ontario Freshwater Fishes Life History Database] contact Robert J. Eakins (creator of the database)
* The code and figures in this GitHub repository are disturbed under a [BSD 3-Clause license]. For alternative licensing arrangements, contact Omar Alminagorta directly. 

## More Information: 
Please contact o.alminagorta@utoronto.ca

[Website of the project]: https://mteproject.weebly.com/
