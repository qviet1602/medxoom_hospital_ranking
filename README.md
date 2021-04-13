# Hospital and Medical Providers Recommendation
## 1. Introduction

## 2. Dataset Overview
1)	Detailed_Data.xlsx : This is the file containing the “labels” for a subset of hospitals from all over the US. The labels could be the standardized price , total allowed amount or relative price(inpatient / outpatient or both). The study that details how exactly the variables in this file are calculated is found [here](https://www.rand.org/health-care/projects/price-transparency/hospital-pricing/round2.html)
2)	Rand_hcris_cy_hosp_a_2020_05_01.csv.zip : This is the zipped full hospital cost report information system (HCRIS) data file having all the financial metrics for all hospitals across several years .The detailed description of each variable in this file is provided in the files in the folder above.
3)	Medicare IPPS and charge data : This dataset contains the utilization and charge data for providers participating in IPPS (from hereby referred to as ‘IPPS hospitals’) for 2011-2017, an example for 2017 can be found [here](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Inpatient2017). You can download files for other years similarly.
5)	Medicare IPPS Final Rule data files : These datasets additional hospital level variables such as Wage Index for Provider , Resident to Bed Ratio - Indirect Medical Education , Disproportionate Share Ratio , Number of Cases , CBSA etc. and other relevant info on inpatient services performed by the IPPS hospitals such as Weights for MS-DRGs(codes used to identify the specific inpatient service), Average length of stay for each etc. You can download all relevant data files from [this page](https://www.cms.gov/Medicare/Medicare-Fee-for-Service-Payment/AcuteInpatientPPS/FY2020-IPPS-Final-Rule-Home-Page-Items/FY2020-IPPS-Final-Rule-Data-Files)
6)	Quality Data : This data contains quality scores for all hospitals and providers in the US along with other variables like Readmissions rate , mortality rate etc. We are working on getting this delivered to you.
7)	Census Data : The American Community Survey(ACS) website provides over 10,000+ metrics on the US  population such as household income , age , healthcare spend etc. at different geographic levels such as county , census tract , zip code etc. They also have apis in different programming languages . We recommend using this particular data set called ACS 5 year data(2009-2018) which is the latest that they have. Check it out [here](https://www.census.gov/data/developers/data-sets/acs-5year.html)
