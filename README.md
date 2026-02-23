# A_statistical_assessment_of_the_EU_packaging_waste_directive_on_PPR_in_the_EU
This repo contatins the data and R code that accompanies the manuscript 'A statistical assessment of the EU packaging waste directive (2004 Amendment) on plastic packaging recycling in the EU'.

# export full.xlsx
This file has the exports data used to calculate net imports of plastic packaging materials. This data was obtained from Eurostat (online data code ds-045409). The data spans 1999-2022.

# import full.xlsx
This file has the imports data used to calculate net imports of plastic packaging materials. This data was obtained from Eurostat (online data code ds-045409). The data spans 1999-2022.

# generation full.xlsx
This file has the data regarding the generation of plastic packaging waste, used in the post-hoc volume trend analysis. The recycling rates from recycling full.xlsx were multiplied by the generation figures in this dataset to estimate the volume of plastic packaging waste recycled. This data was obtained from Eurostat (DOI 10.2908/env_waspac). The data spans 1999-2022.

# recycling full.xlsx
This file has the data regarding the recycling rates of plastic packaging waste, used in the interrupted time series analysis. This data was obtained from Eurostat (DOI 10.2908/env_waspac). The data spans 1999-2022.

# europeanSims.R
This file carries out the statistical power and type I simulations which are detailed in the appendix of the manuscript.

# europeanITS.R
This files calculates net imports of plastic packing materials using the above data from exports full.xlsx and imports full.xlsx. 

Then, the interupted time series analysis is performed for each of the 13 countries, using the net imports as a covariate and the data from recycling full.xlsx as the dependent. 

This file carries out the volume trend analysis. The recycling rates from recycling full.xlsx are multiplied by the corresponding generation value in generation full.xlsx to estimate the volume of plastic packaging waste recycled in each of the 13 countries in each year between 1999-2022. This, along with the raw values of plastic packaging generation from the generation full.xlsx file are used to perform the volume trend analysis. 

This file also creates the plots used form the publication.
