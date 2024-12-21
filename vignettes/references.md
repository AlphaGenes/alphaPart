Here is a list of some:
* classic references for genetic trend estimation,
* methodological and software references for the partitioning method, and 
* some cases of using the partitioning method

## Classic references for genetic trend estimation

* Henderson et al. (1959) The Estimation of Environmental and Genetic Trends from Records Subject to Culling. Biometrics, 15(2)192-218. https://doi.org/10.2307/2527669

* Blair and Pollak (1984) Estimation of Genetic Trend in selected Population with and Without the use of Control Population. Journal of Animal Science, 58(4):878–886. https://doi.org/10.2527/jas1984.584878x

* Sorensen and Kennedy (1984) Estimation of Response to Selection Using Least-Squares and Mixed Model Methodology. Journal of Animal Science, 58(5):1097–1106. https://doi.org/10.2527/jas1984.5851097x

* Sorensen et al. (1994) Bayesian analysis of genetic change due to selection using Gibbs sampling. Genetics Selection Evolution, 26:333. https://doi.org/10.1186/1297-9686-26-4-333 (Full probablistic analysis of the mean of breeding values over time - providing a full posterior distribution.)

* TODO: Add other key classic references 
## References for the partitioning method
* 	Woolliams et al. (1999) Expected Genetic Contributions and Their Impact on Gene Flow and Genetic Gain. Genetics, 153(2): 1009–1020. https://doi.org/10.1093/genetics/153.2.1009 (Describes the flow of the genes through the pedigree by decomposing pedigree relationship matrix.)

* García-Cortés et al. (2006) Multibreed analysis by splitting the breeding values. Genetics Selection Evolution, 38(6):601-615. https://doi.org/10.1051/gse:2006024 (Developed a quantitative genetics model with additive genetic values that are split into several independent parts depending on their genetic origin.)

* García-Cortés et al. (2008) Partition of the genetic trend to validate multiple selection decisions. Animal, 2(6):821-824. https://doi.org/10.1017/S175173110800205X (The original publication proposing the partitioning method.)

* García-Cortés et al. (2010) Fine decomposition of the inbreeding and the coancestry coefficients by using the tabular method. Conservation Genetics 11:1945–1952. https://doi.org/10.1007/s10592-010-0084-x (Developed a simple algorithm to decompose both inbreeding and coancestry coefficients by each ancestor, including the founders and the Mendelian sampling terms of non-founders.)

## Methodological and software references for the partitioning method

* Škorput et al. (2015) Partition of genetic trends by origin in Landrace and Large-White pigs. Animal, 9(10):1605-1609.
https://doi.org/10.1017/S1751731115001056 (Partitioned genetic trend by domestic and import contributions. Used samples from posterior distribution to quantify uncertainty in the total and partitioned genetic trends.)

* Obšteter et al. (2021) AlphaPart — R implementation of the method for partitioning genetic trends. Genetics Selection Evolution, 53:30. https://doi.org/10.1186/s12711-021-00600-x (R implementation of the partitioning method with a two-stage selection example.)

* Oliveira et al. (2023) A method for partitioning trends in genetic mean and variance to understand breeding practices. Genetics Selection Evolution 55:36. https://doi.org/10.1186/s12711-023-00804-3 (Extends the partitioning method to use any function in addition to the mean of breeding values, say variance. Provided implementation in the AlphaPart R package.)

* Lopez-Carbonell et al. (2024) Multiple Trait Bayesian Analysis of Partitioned Genetic Trends Accounting for Uncertainty in Genetic Parameters. An Example With the Pirenaica and Rubia Gallega Beef Cattle Breeds. Journal of Animal Breeding and Genetics, TODO. https://doi.org/10.1111/jbg.12918 (Partitioned genetics trends for five traits in two breeds by six categories of animals: non-reproductive individuals, dams of females and non-reproductive individuals, dams of sires, sires with fewer than 20 progeny, sires between 20 and 50 progeny, and sires with more than 50 progeny. Sires with more than 50 progenies and dams of males were the key drivers. They also show posterior probability of the global and partitioned genetic response between two time points, and the calculation of the posterior probability of positive (or negative) genetic progress. Provided software TM_TRENDS (extension of TM) to estimate breeding values, variance components, and partitions in one joint analysis.)
## Some use cases of the partitioning method

* Gorjanc et al. (2011) Partitioning of international genetic trends by origin in Brown Swiss bulls. Interbull Bulletin, 44:81-86. https://journal.interbull.org/index.php/ib/article/view/1689 (Partitioned international/world-wide genetic trend by country of origin, showing a significant contribution from USA on increasing protein yield, initially increasing and later improving somatic cell score, increasing calving to conception, and initially decreasing and later improving longevity.)

* Spehar et al. (2011) Partitioning of Genetic Trends by Origin in Croatian Simmental Cattle. Agriculturae Conspectus Scientificus, 76(4):301-304. https://hrcak.srce.hr/72103 (Partitioned genetic trend into local and import contributions for different traits and showed significant contribution from both sources. These contributions change as the asssumed based population changes.)

* Gorjanc et al. (2012) Partitioning international genetic trends by origin in Holstein bulls. ICAR. https://www.icar.org/Cork_2012/Presentations/T1%20Gorjanc_PPT.pdf (Partitioned international/world-wide and national genetic trends for total merit index (TMI) by country of origin. Four TMI defined in four countries were analysed. The results showed dominating positive and negative
effect of USA on the global TMI trends, while local TMI trends can deviate considerably
from global trends due to country specific breeding practices.)

* See also Škorput et al. (2015) above for application in pig genetic trends.

* Skorput et al. (2018) Partition of genetic trend for daily gain by sex in Landrace, Large White, Pietrain, and Duroc pigs. Journal of Central European Agriculture, 19(3):648-657. https://doi.org/10.5513/JCEA01/19.3.2130 (Partitioned genetic trends by sex, showing larger contribution of males.)

* Abdollahi-Arpanahi et al. (2021) Dissecting genetic trends to understand breeding practices in livestock: a maternal pig line example. Genetics Selection Evolution: 53, 89. https://doi.org/10.1186/s12711-021-00683-6 (Partitioning genetic trends of pedigree-based and genome-based estimated breeding values by genotyped and non-genotyped individuals. This analysis enabled them to indicate when genomic selection has been introduced into a breeding programme.)

* Spehar et al. (2022) Partitioning of genetic trends by flock and gender in Istrian sheep breed. Proceedings of 12th World Congress on Genetics Applied to Livestock Production (WCGALP): 2968-2971. https://doi.org/10.3920/978-90-8686-940-4_720 (Partitioned genetic trends by sex and flock, showing larger contribution of males and no significant differences between flock contributions.)

* Obšteter et al. (2023) Investigating the benefits and perils of importing genetic material in small cattle breeding programs via simulation. Journal of Dairy Science, 106(8):5593-5605. https://doi.org/10.3168/jds.2022-23132 (Partitioned genetic trends by national and import contribution to evaluate positive and negative effects of import under different genetic correlations.)

* Antonios et al. (2023) Partitioning of the genetic trends of French dairy sheep in Mendelian samplings and long-term contributions. 
Journal of Dairy Science, 106(9):6275-6287. https://doi.org/10.3168/jds.2022-23009 (Partitioned the genetic trend by the following groups of animals: artificial insemination males (after progeny testing), males discarded after progeny testing, natural mating males, dams of males, and dams of females. Dams of males and AI males were the most important drivers of genetic gain.)

* Pardo et al. (2023) An insight into population structure and genetic progress of Argentinean Holstein cattle. Journal of Animal Breeding and Genetics; 140(4):376–389. https://doi.org/10.1111/jbg.12766 (Partitioned genetic trends for several traits by sex and country of origin over a long period  (1936 to 2019). Observed that import had a significant contribution to genetic gain in the population.)

* See also Lopez-Carbonell et al. (2024) above for application in beef genetic trends.