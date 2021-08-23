# MRes Dissertation as part of the EPSRC Centre for Doctoral Training (CDT) in Geospatial Systems 

This repository contains all the code developed as part of the MRes research project for the year 2020-2021.

> The final document will be uploaded after receiving the marks and feedback

# ADD TITLE OF THE DISSERTATION

## Motivation, Aim and Objectives

The motivation of this study was the interest to understand how precipitation-related extremeswill affect water security, at regional scales, particularly in the creation of actionable knowledgefor policy and decision making processes (Lopez et al., 2020; Nicholson et al., 2009). UnitedNations (2013), defined water security as a condition based on the ability of the population toaccess adequate volumes of clean water to enable sustain livelihoods, as well as including theprotection of livelihood against water related natural disasters. Over the past two decades severalstudies have presented results showing a projected increase in the frequency and intensity ofprecipitation events, with the majority of these studies used as part of the AR6 published by theIPCC in August 2021, corroborating that the frequency and intensity of precipitation-relatedevents is very likely to increase on the global scale (virtually certain) when compared to therecent past (Seneviratne et al., 2021).

However, before assessing the impact of precipitation-related extremes over water security ata regional level, a greater understanding of extreme precipitation concepts and analysis techniquesneed it to be developed by the author of this study. From this perspective, the main purpose ofthe present study is bifold. First; this study aims to enable the development of knowledge andunderstanding of concepts and elements of precipitation-related extremes through the evaluationof annual precipitation and extreme indices in the UK using observational, satellite-derivedand reanalysis products.  Second; to inform the development of a PhD level research in howprecipitation-related extremes will affect water security at a regional level. The following are theobjectives outlined for this study:

- calculate the set of annual precipitation and extremes indices as defined by the ETCCDIfor the UK using gauge, satellite-derived and reanalysis products,

- evaluate the spatio-temporal performance of the set of indices for each dataset based on (a)arithmetic differences and (b) descriptive statistics,

- use the outcomes of the study to evaluate future research and development with regards tothe effects of precipitation-related extremes over water security

## Abstract

The objectives of this study were to evaluate the spatio-temporal performance of a suite ofannual precipitation and extremes indices obtained from in-situ (HadUK-Grid), satellite-derived(IMERG) and reanalysis (ERA5) precipitation products over the United Kingdom of Great Britainand Northern Ireland (UK). Extreme indices such as the number of days with a precipitationvalue over 10 mm, the maximum duration of wet and dry days, and total precipitation higherthan the 95thpercentile, among six others, were calculated using a Python based library witha set of functions built using xarray (i.e. xclim) over the climatological period 2001-2019 onseasonal time scales.  In addition, extreme indices computed from in-situ and reanalysis datawere regridded at 10x10 km spatial resolution to match the extreme indices computed usingsatellite-derived data. Extreme precipitation indices from satellite-derived and reanalysis datasetswere compared to in-situ data based on the magnitude of difference and statistical significance.The findings showed a similar spatial distribution for the suite of annual precipitation andextremes indices computed from all datasets with moderate mean correlation values (>=0.6) across the study area. However, in terms of their magnitude the range of precipitation extremeindices showed significant variability over space and time. Overall, results showed that in-situ,satellite-derived and reanalysis precipitation products showed sufficient and similar informationto inform long-term trends of precipitation-related extreme, as well as a significant level ofuncertainty related to the magnitude of trends for areas with an abundance of in-situ data such asthe UK

## References

Lopez, A., Coughlan de Perez, E., Bazo, J., Suarez, P., van den Hurk, B., and van Aalst, M.(2020).  Bridging forecast verification and humanitarian decisions:  A valuation approachfor setting up action-oriented early warnings.Weather and Climate Extremes, 27(March2018):100167.

Nicholson, E., MacE, G. M., Armsworth, P. R., Atkinson, G., Buckle, S., Clements, T., Ewers,R. M., Fa, J. E., Gardner, T. A., Gibbons, J., Grenyer, R., Metcalfe, R., Mourato, S., Muûls,M., Osborn, D., Reuman, D. C., Watson, C., and Milner-Gulland, E. J. (2009).   Priorityresearch areas for ecosystem services in a changing world.Journal of Applied Ecology,46(6):1139–1144

United Nations (2013).  UN-Water: Water security and the global water agenda – a un water analytical brief, United Nations University, Hamilton, Canada.

Seneviratne, S. I., Zhang, X., Adnan, M., Badi, W., Dereczynski, C., Luca, A. D., Ghosh, S.,Iskandar, I., Kossin, J., Lewis, S., Otto, F., Pinto, I., Satoh, M., Vicente-Serrano, S. M.,Wehner, M., and Zhou, B. (2021). Weather and climate extreme events in a changing climate.In of Working Group I. to the Sixth Assessment Report of the Intergovernmental Panel onClimate Change [Masson-Delmotte, C., V., P. Z., Pirani, A., Connors, S. L., Péan, C., Berger,S., Caud, N., Chen, Y., Goldfarb, L., Gomis, M. I., Huang, M., Leitzell, K., Lonnoy, E.,Matthews, J. B. R., Maycock, T. K., Waterfield, T., Yelekçi, O., Yu, R., and Zhou, B., editors,Climate Change 2021: The Physical Science Basis. Cambridge University Press, In Press.