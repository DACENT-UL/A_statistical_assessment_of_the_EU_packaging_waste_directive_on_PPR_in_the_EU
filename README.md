# A_statistical_assessment_of_the_EU_packaging_waste_directive_on_PPR_in_the_EU
This repo contatins the data and R code that accompanies the manuscript 'A statistical assessment of the EU packaging waste directive (2004 Amendment) on plastic packaging recycling in the EU'.

# export full.xlsx
This file has the exports data used to calculate net imports of plastic packaging materials

# import full.xlsx
This file has the imports data used to calculate net imports of plastic packaging materials

# generation full.xlsx
This file has the data regarding the generation of plastic packaging waste, used in the post-hoc volume trend analysis

# recycling full.xlsx
This file has the data regarding the recycling rates of plastic packaging waste, used in the interrupted time series analysis

# europeanSims.R
This file carries out the statistical power and type I simulations which are detailed in the appendix of the manuscript.

# europeanITS.R
This files calculates net imports of plastic packing materials using the above data from exports full.xlsx and imports full.xlsx. 
Then, the interupted time series analysis is performed for each of the 13 countries, using the net imports as a covariate and the data from recycling full.xlsx as the dependent.
This file also creates the plots used form the publication.
