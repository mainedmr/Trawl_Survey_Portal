
# Welcome

Welcome to the state of Maine Department of Marine Resources ME-NH Inshore Trawl Survey Data Portal. This portal contains summary results from the survey. You will find graphs of abundance and biomass indices and length frequency for each species over the survey time period. Environmental data collected on the survey is also available along with maps depicting the spatial distribution of catch in each survey.

**For temperature data and spring 2022 data please contact Robyn.Linner@maine.gov**
**In the spring of 2022 we had a delay in the first two regions of the survey. Regions 3, 4, and 5 were completed around the same time as previous years. Regions 1 and 2 were delayed by about four weeks (they were completed after the original end date of the survey).**

### About the survey

The [Maine-New Hampshire Inshore Trawl Survey](https://www.maine.gov/dmr/science/fisheries-monitoring-assessment/maine-new-hampshire-inshore-trawl-survey) is a fishery-independent survey operated by Maine Department of Marine Resources that started in the fall of 2000. The survey is a collaborative partnership between commercial fishermen and state researchers to assess inshore fish stocks along the coast of Maine and New Hampshire. The survey occurs twice a year, in the spring and fall, and covers about 4500 square miles. A more detailed description and protocols for the survey can be found [here](https://www.maine.gov/dmr/sites/maine.gov.dmr/files/docs/proceduresandprotocols.pdf). Reports and publications from the ME-NH trawl survey can be accessed [here](https://www.maine.gov/dmr/science/fisheries-monitoring-assessment/maine-new-hampshire-inshore-trawl-survey-data-dashboard).

#### Survey Design

The ME-NH survey is a stratified random survey, seperated into four depth strata and five geographic regions along the coast of Maine and New Hampshire. The inner boundary is defined by the shallowest depth that the 55-ft survey vessel can effectively sample (about 5 meters) and the deeper boundary loosely follows the 12 mile limit. One hundred and twenty stations are randomly selected for sampling before the start of each spring survey. The randomly selected sites that were sucessecfully sampled in the spring are resampled again in the fall. The goal is to complete one, twenty minute, tow using a modified shrimp net at each randomly selected station. However, sometimes due to bottom the tow is moved or shortened. After the tow is completed, the catch is brought on board and sorted by species. The total weight of each species is weighed and then lengths are measured. Most species are measured to the nearest centimeter, except for lobsters, scallops, and urchins which are measured to the nearest millimeter. Finfish are measured for total centerline length, lobsters and northern shrimp for carapace lengths, crab species for carapace width, scallops for shell height, squid for mantle length, and octopi are measured out to the longest arm. If there is a large catch of a species a subsample is taken and 100 individuals are randomly selected for measurement. Selected species are sampled for maturity and age samples each survey.


<p align="center">
<img width="750" height="550" src="https://github.com/mainedmr/Trawl_Survey_Portal/raw/master/Images/MENH_SurveyDesign_Updated11.19.jpg">
</p>

### Portal Description

In the portal there are five tabs where data from the survey are summarized and displayed. 

* The **Species Indices** tab displays the stratified mean catch (number/tow) and weight (kg/tow) of every species caught in the survey. There are selectors on the side to select a species to view these indices over time. _Note: All abundance and biomass indices are calculated using all four depth strata. If you need specific data for stock assessments please contact Rebecca Peters with a request._

* The **Catch at Length** tab shows the length frequency of each species caught in the survey over time. There are selectors on the side to select a species and season.

* The **Species Distribution Map** displays the number of a selected species caught in each tow of a selected survey. You can hover over a dot to look at the number caught in that location. Black dots with x's in them indicate the selected species was not caught in that tow. If you click on a dot you can view the lengths of the selected species caught in that location. There are two map choices on this page: single survey (just displays one year of survey data), or time series (allows you to view average catch by survey sampling grid over a range of years). There are drop downs to allow you to select a specific species, survey, and year. You are also able to select the option to view number caught or catch weight (kg) in each location.

* The **Maturity Data** tab shows data on sex and maturity stage collected on a select species of finfish sampled in the spring and fall surveys. There are only select species sampled depending on the season of the survey. The table below describes which species are sampled each season. When you are on this tab you will have to pick the correct season in which the species is sampled to view the data. If no graph shows up when you select a specific species, survey, and year this means there is no data for that species in that season or year. Check this table to make sure you have the correct season selected for the species of interest. All maturity staging follows protocols from Burnett et al. 1989.

<p align="center">
<img width="300" height="200" src="https://github.com/mainedmr/Trawl_Survey_Portal/raw/master/Images/Species_Maturity_list.jpg">
</p>

* The **Enviromental Data** tab allows you to view average temperature in the survey over time. You are able to select between spring and fall. **for spring data please contact Robyn Linner (Robyn.Linner@maine.gov).**

* The **Download Raw Data** tab allows you to view and download data collected from the survey ONLY if you received proper permissions to download the data. If you are signed in as a public user then you do not have access to this page. There are five choices to view and download: Tow Data, Catch Data, Length Data, Lobster Length Data, and Maturity Data. The Tow Data option allows you to view general information for each tow of each survey. Some data in this tab includes GPS data, bottom and surface water temperature, bottom and surface salinity, start and end depth, and tow length. The Catch Data tab allows you to view the standardized catch (labeled as expanded_catch and expanded_weight) from each tow from each survey. You will also see a column labeled Number Caught and weight kg. These columns are the raw (not standardized catch and weight of each species). The Length Data and Lobster Length Data include the lengths, measurement unit, and standardized frequency of each length caught for each species in each tow of the surveys. The standardized frequency accounts for any subsample and tow length under or over 20 minutes. The Maturity Data includes data on maturity on the species we select each survey to take sex and maturity information from. To stage maturity we follow Burnett et al. 1989. Our stages are Immature (I), Developing (D), Ripe ( R), Ripe and Running (U), Spent (S), and Resting (T).


If you have any questions or would like additional data please contact [Robyn Linner](https://www.maine.gov/dmr/about/employees.html).


### Technicalities

* In the spring of 2022 we had a delay in the first two regions of the survey. Regions 3, 4, and 5 were completed around the same time as previous years. Regions 1 and 2 were delayed by about four weeks (they were completed after the original end date of the survey). We do not recommend using the whole time series for average temperature as it is displayed here. Please contact [Robyn Linner](https://www.maine.gov/dmr/about/employees.html) if you have any questions.

#### Bug Reports

Found a bug or have an idea for an enhancement? [Submit an issue on GitHub](https://github.com/mainedmr/Trawl_Survey_Portal/issues)
