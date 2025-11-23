# medicare-drug-spending

# Data Cleaning
- Brand Name that had an asteric were combined with their counterparts to combine all types of administered drugs.
- 
# Data Dictionary


|Column Name|Column Abbreviation|Definition|
|------|-------|---------|
|Brand Name|Brnd_Name|The name of the drug filled. This includes both brand names (drugs that have a trademarked name) and generic names (drugs that do not have a trademarked name). ' * ' indicates that the average spending per dosage unit reflects multiple routes of administration of the drug (e.g., intravenous, subcutaneous) which individually may have different unit pricing. Additional information regarding calculation of spending per unit can be found in the methodology document.|
|Generic Name|Gnrc_Name|A term referring to the chemical ingredient of a drug rather than the trademarked brand name under which the drug is sold.|
|Number of Manufacturers|Tot_Mftr|Number of Manufacturers for each drug.|
|Manufacturer|Mftr_Name|Name of manufacturers of the drug.|
|2019 Total Spending|Tot_Spndng_2019|Aggregate drug spending for the Medicare Part D program during the benefit year.|
|2019 Total Dosage Units|Tot_Dsg_Unts_2019|The sum of the dosage units of medication dispensed across the calendar year (e.g. number of tablets, grams, milliliters or other units). Unit refers to the drug unit in the lowest dispensable amount.|
|2019 Total Claims|Tot_Benes_2019|Number of Part D beneficiaries utilizing the drug during the benefit year.|
|2019 Average Total Spending Per Dosage Unit (Weighted)|Avg_Spnd_Per_Dsg_Unt_Wghtd_2019|Medicare Part D drug spending divided by the number of dosage units, which is weighted by the proportion of total claims.|
|2019 Average Total Spending Per Claim|Avg_Spnd_Per_Clm_2019|Part D drug spending divided by the number of prescription fills.|
|2019 Outlier Flag|Outlier_Flag_2019|Yearly outlier flag variable, which is set to “1” when a drug’s Average Spending per Dosage Unit is substantially impacted by outlier records in a given year. These potentially anomalous drugs are identified as outliers so that users can exercise caution when interpreting results.  See the methodology document for additional details.|
|Change in Average Total Spending Per Dosage Unit (2022-2023)|Chg_Avg_Spnd_Per_Dsg_Unt_22_23|The percent change in average spending per dosage unit from the prior year.|
|Annual Growth Rate in Average Total Spending Per Dosage Unit (2019-2023)|CAGR_Avg_Spnd_Per_Dsg_Unt_19_23|The constant average change in spending per dosage unit over the most recent five years of data availability, calculated using the compound annual growth rate (CAGR).|

Note: The column names beginning with 2019 repeat for 2020-2023, and are not repeated in the table. Assume same definitions for other years as what is listed as the definitions for 2019 column names.
View this information on the website [here.](https://data.cms.gov/resources/medicare-part-d-spending-by-drug-data-dictionary)
