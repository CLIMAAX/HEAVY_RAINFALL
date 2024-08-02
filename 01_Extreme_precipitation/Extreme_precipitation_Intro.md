# Heavy rainfall
## Extreme precipitation - workflow for risk assessment under climate scenarios

This workflow is designed to help in exploring the local and regional risks presented by heavy rainfall (extreme precipitation), and assessing the impact of climate change on these risks.

Extreme precipitation is characterized by the occurrence of a large amount of rainfall within a short timeframe. The frequency and intensity of such extreme precipitation events are likely to change under the influence of climate change. These projected changes can translate to an increase in the frequency and magnitude of pluvial floods (urban and flash floods), as these result from the precipitation intensity exceeding the _critical rainfall thresholds_ of natural and artificial drainage systems capacities. 

### Risk assessment methodology
The extreme precipitation workflow has been constructed to guide users, communities, and regions in understanding how their current critical impact-based rainfall thresholds (in terms of magnitude, duration and frequency) will be affected by climate change for specific locations or entire regions. Risk is assessed as a function of precipitation intensity, associated with a critical impact-based rainfall threshold, and its potential magnitude and frequency variations due to climate change. The explanation of the concept of the critical impact-based rainfall thresholds and a step-by-step guide on developing and identifying these are included in the workflow. 

### Hazard assessment under climate change
This workflow makes use of the information on the changes in precipitation for specific durations, return periods, Global-Regional climate model pairs and RCPs (Representative Concentration Pathways). This information can be used to identify whether the local critical impact rainfall thresholds for infrastructures, vulnerable locations or areas are exceeded (or not) under the influence of climate change scenarios.  

In this analysis we use the EURO-CORDEX climate projections for precipitation flux at a 12 km spatial resolution. These projections are openly available to the public through the Climate Data Store portal. As an example within the workflow, the timeframes 1976-2005 and 2041-2070 are used to represent historical simulations and climate projections, respectively.   

### Structure of the workflow
This workflow consists of several parts, where the user in guided in performing a risk assessment for heavy rainfall step by step, using climate data analysis supplemented with local information. In the next pages you will find:
1. **Local data requirements and interpretation for climate risk assessment** (see next page) - Guidance on what are impact rainfall thresholds, the local knowledge to derive them, and a summary of the basic information needed to start executing the extreme precipitation workflow.   
2. **Heavy rainfall hazard assessment using climate projections ([notebook](https://github.com/CLIMAAX/HEAVY_RAINFALL/blob/main/EXTREME_PRECIPITATION_Hazard_Assessment.ipynb))** - technical background information and code on how to use climate projection data to calculate precipitation intensities and return periods for a specific Global-Regional climate model chain and RCP. We use Catalonia region in Spain as an example and provide text to guide you on how the code can be modified according to your research interest. 
*Note: This section is meant for advanced users and is not strictly necessary to start with the risk assessment - pre-calculated hazard data is also available.*   
3. **Risk assessment methodology ([notebook](https://github.com/CLIMAAX/HEAVY_RAINFALL/blob/main/EXTREME_PRECIPITATION_Risk_Assessment.ipynb))** - technical background and code on how to use hazard data to assess future risks due to heavy rainfall - a climate risk assessment methodology for extreme precipitation. We have used Catalonia and the city of Blanes as regional and location-specific examples to guide you on how the code can be modified according to your research interest.
4. **Risk assessment examples ([notebook](https://github.com/CLIMAAX/HEAVY_RAINFALL/blob/main/EXTREME_PRECIPITATION_Risk_Assessment_examples.ipynb))** - Real examples on how to use the extreme precipitation workflow to carry out a regional and local risk assessment.

### Outputs of the workflow
The objective of the extreme precipitation is to explore how the current critical impact-based rainfall thresholds will vary in terms of frequency and magnitude. Therefore, the output is conditioned to the two types of risk analysis presented in this workflow, for a specific location within an area of interest (site-specific risk assessment) or an entire analysis area (regional risk assessment).   

For a specific location, the changes in magnitude (%) and return period values (frequency) can be directly printed (e.g., *“For the period of 2041-2070, if we would like to maintain the same rainfall magnitude of our current critical threshold, the frequency will change from a 25 year to 10-year return period”*).   

For the regional risk assessment, visualisations can be developed to better understand the changes in magnitude and frequency of the current regional critical thresholds. For example, the image below illustrates the shift in frequency of the local critical threshold of 100mm per 24 hours between current-day climate and the climate in the future (2041-2070) under RCP8.5 for Catalonia. 

![Example_precipitation_change](https://github.com/CLIMAAX/HEAVY_RAINFALL/blob/main/images/output_extreme_rainfall_frequency_shift_Catalonia.png?raw=true "Extreme precipitation illustration")
 
We encourage you to explore the extreme precipitation workflow on your region!
