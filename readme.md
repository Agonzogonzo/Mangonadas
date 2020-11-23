# Policing Proximate to Hazards Updated 11/22
By Danielle Hoague & Andres Gonzalez
-----

## Introduction
-  According to the [2019 World Air Quality Report] (https://www.iqair.com/us/usa/california/los-angeles), Los Angeles county contains 9 of the 15 most polluted cities in the United States using PM 2.5 metrics. Our City is polluted, and in some places more than others. Contamination from heavy metals and other toxic pollutants continues from the legacies of redlining, segregation, and discriminatory land use practices by localizing hazardous materials in Black, Indigenous, Latin, Asian and Pacific Islander communities. We plan to examine the overlaps between policing and environmental hazards in the city of Los Angeles by census tract. 
Often, the mental and psychological issues that arise from exposure to toxic materials can result in socio-behavioral issues that are interpreted by law enforcement and other community members as a threat or violent behavior. This phenomenon could be even more commonplace in communities that are already over-policed; where minor instigations can result in excessive violence and suppression by law enforcement officers. From our preliminary research, we are seeing that this enhanced pathway of toxic exposures requires further exploration. 

### *Our research seeks to understand: Are communities that are proximate to environmental health hazards more policed than those not as exposed by environmental health hazards?* 

## Explanation

- Exposure to pollution can cause a plethora of negative health outcomes including degraded mental and physical health . Mental health conditions can manifest from unremediated exposure to ambient air pollution containing a mix of compounds including particulate matter (PM), nitrogen dioxide (NO2), carbon monoxide (CO), and sulfur dioxide (SO2) [(NCBI, 2018)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5891065/#:~:text=A%20growing%20body%20of%20evidence,to%20air%20pollutants%20%5B2%5D.). According to a review published in the Journal of Urban Design and Mental Health, there is a paucity of evidence that mental health is correlated with ambient air pollution because there are confounding factors such as urban access to green space, vegetation, density and high rise living [(UD/MH,2018)](https://www.urbandesignmentalhealth.com/journal-4---air-pollution-and-mental-health.html).
- According to research in the US and denmark, proximity to these environmental pollutants can have long lasting neurological impacts and can stunt childhood development [(Khan et al., 2019)](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3000353). This medical evidence could be a piece of an outstanding issue facing at-risk communities. 
- Behaviors associated with mental health conditions could be criminalized or deemed as “deviant”, despite that there could be an underlying cause for degraded social conditions. Due to the perceptions of mental health concerns by law enforcement and communities, those who have been exposed by environmental hazards could be perceived as a threat to public safety.

## Spatial scope
- Using 2019 Geohub Los Angeles data, we will examine if pollution correlates with excessive policing in the city of Los Angeles. We will overlay arrest data with environmental hazard data by census tract in Los Angeles. The integration of data sources will take place on the census tract level. 
- We anticipate that our main challenge will be providing statistically significant data overlaying these two features of vulnerable communities of color, many who are already overpoliced. 
- *Our data isolates key crimes and background ejsm scores, primarily census tracts that score high in relationship to environmental hazards, such as pollutants and waste sites. While we've struggled to create a statistical significant correlation we are able to see a greater accumulation of crimes, particularly aggravated assaults, areas proximiate to environmental hazards.*
- *Through R and qualitative methods we hope to shed further light on the scope of our project. Will there be a correlation with sites? How will the year the EJSM data was made affect the correlation and longitudinal understanding of arrest data in high scoring census tracts?*
 

## Data Description
- We will be using real-time arrest data from GeoHub LA. Our analysis will include data from January 2020-present. 
- Our [arrest data](https://dev.socrata.com/foundry/data.lacity.org/amvf-fr72) is transcribed from LAPD paper reports. There are 21 community police stations defining the geographic areas of their communities. *These reports are specific to the City of Los Angeles,* and are updated daily. 
- The Geohub Environmental Justice Screening Method (EJSM) data is sourced from the [California Office of Health Hazard Assessment](https://oehha.ca.gov/calenviroscreen/maps-data). *The EJSM data represents environmental health information about Los Angeles County.* The dataset 
is defined by the cumulative impacts of social and health vulnerability, health risk and risk exposure, climate change vulnerability, and hazard proximity and sensitive land uses. [EJSM scores](https://geohub.lacity.org/datasets/lacounty::ejsm-scores) For the purposes of our project, we will be focusing on the hazard proximity and cumulative impact scores. 
-Our arrest and EJSM score data will overlap with the City of LA, and leave some spaces between jurisdictions. 

## Scope
- We hope to understand what kind of policing occurs and compare different arrest types and charges to a census tract’s proximity to environmental hazards. 
-We intend to further explore the intersections between purportedly aggressive behaviors and proximity to environmental harms. Both of these factors leave residents susceptible to further harms to their physical and mental health. 
-*Our scope can potentially include temporal data and long term arrest impacts. If we were to overlay it with specific hazards, such as the Exide battery plant, and it's founding and closure, we could see, and potentially even predict the degree of arrests in a particular census tracts based on the delayed and long-lived health impacts of heavy metals in these areas*

## Conclusion:
- We anticipate finding that particularly in Black and Brown communities there could be elevated levels policing compared to the average in Los Angeles. Our main objective is to see if crime incident data rates variate based on areas experiencing greater amounts of vulnerability due to environmental health hazards. 
- We hypothesize that there could be a significantly greater level of policing in these areas than the average of Los Angeles and of neighboring census tracts. Furthermore, we predict that crimes reported connected to mental health issues (like aggravated assault) could be significantly greater in census tracts closer to proximity to census tracts containing more pollution sources. 
- We hope to visulaize these connections between policing and environmental hazards because these factors are crucial to understanding which landscapes are at a higher risk of being exposed to police brutality. 
- *Our initial visualizations show that crimes as a whole do occur more in census tracts that score higher on Hazard scores, and cumulative impact scores (an index of various index variables including social vulnerability, proximity to hazarrds, and climate vulnerability). While this isn't suprising, it also becomes apparent that specific arrests such, as aggravated assault, do have a greater tendency to occur in high scoring census tracts relative to proximity to hazards, especially in downtown and south LA. Our two other indicators, disturbing the peace, and disorderly conduct, were very rare charges and didn't occur with enough frequency in our sample size to confidently say they occured due to policing of the socio-behavioral impacts from proximity to environmental hazards*
- *Next steps can include creating an index of our own making, and running a statistical analysis or a regression to identify how policing is shaped by, and responds to, the health impacts of environmental hazards on communities that are most exposed. Another element to possibly explore are the temporal dynamics, and the qualtiatve research required to understand the timelines and histories of contamination in these areas.*


## Resources: 

*[Team MangoNadas Github](https://github.com/Agonzogonzo/Mangonadas)*

*Locating areas of interest*
https://oehha.ca.gov/calenviroscreen/maps-data
https://geohub.lacity.org/datasets/lacounty::hazardous-waste-disposal

*California Dept of Public Health general information*
https://www.cdph.ca.gov/Programs/CCDPHP/DEODC/Pages/Environmental-Health-Topics.aspx


*EJSM metadata description*
https://www.arcgis.com/sharing/rest/content/items/ba1e513f3fd84029bd8888e2374e75c8/info/metadata/metadata.xml?format=default&output=html

*Citations*

Khan A, Plana-Ripoll O, Antonsen S, Brandt J, Geels C, et al. (2019) Environmental pollution is associated with increased risk of psychiatric disorders in the US and Denmark. PLOS Biology 17(8): e3000353. https://doi.org/10.1371/journal.pbio.3000353

King, Jacob. (2018). Air Pollution, mental health, and implications for urban design: a review. *Journal of Urban Design and Mental Health*. 4:6 https://www.urbandesignmentalhealth.com/journal-4---air-pollution-and-mental-health.html

Shin, J., Park, J. Y., & Choi, J. (2018). Long-term exposure to ambient air pollutants and mental health status: A nationwide population-based cross-sectional study. PloS one, 13(4), e0195607. https://doi.org/10.1371/journal.pone.0195607


![Captain Planet](https://github.com/Agonzogonzo/Mangonadas/blob/Additional-Materials/captain_planet.gif)
