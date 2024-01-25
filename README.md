# git_SpatialOverlap_3Species

Data and code to calculate within-population spatial overlap in Tao et al. 2023.

`data/NS_stn_1965_2000.csv` and `data/NS_stn_2001_2020.csv` are raw CPUE data downloaded from the ICES data portal <https://data.ices.dk>.

`data/total_stock_biomass.csv` are total stock biomass data compiled from two ICES stock assessment reports (ICES 2021, 2023).

`data/bottomT_NS_1977_2019.csv` is sea bottom temperature compiled from yearly raw CTD and Bottle Data, downloaded from the ICES data portal <https://data.ices.dk>. Raw data and codes for compilation can be requested to the author.

`spatial_overlap_analysis_20240119.Rmd` is a R script which reproduces all the results in the manuscript.

# Citations

Tao, H. H., C. W. Chang, and C. H. Hsieh (2023) Spatial segregation between length groups within fish populations under warming and population size decline. Ecography. DOI: 10.1111/ecog.06730

ICES. 2021. Inter-benchmark protocol of North Sea Whiting (IBPNSWhiting). ICES Sci. Rep. 3: 34. 38pp. <https://doi.org/10.17895/ices.pub.7924>

ICES. 2023. Working group on the assessment of demersal stocks in the North Sea and Skagerrak (WGNSSK). ICES Sci. Rep. 5: 39. 1072pp. <https://doi.org/10.17895/ices.pub.22643143>
