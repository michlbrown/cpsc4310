# Dataset Descriptions
### Michael Brown and Alexander Erickson


## American Community Survey
### acs.csv
Obtained through custom tables on census.gov
Processed initially (see Data Prep Jupyter Notebook)

#### Description: 
A combined dataset of the ACS's demographic, economic, housing, and social characteristics.
Only the estimates have been included in this data, error metrics and percentages have been removed.

#### Size
29567 rows × 31 columns

#### Samples
Head:
|FIELD1|ave_household_size|p_highschool_plus|p_bachelors_plus|p_native_born|p_unemployed|p_occ_business_science_art|p_occ_service|p_occ_sales_office|p_occ_resources_construction|p_occ_production_transport|med_household_income|mean_houshold_income|p_families_poverty|p_household_owner_occupied|p_household_renter_occupied|p_grapi_15|p_grapi_15-19.9|p_grapi_20-24.9|p_grapi_25-29.9|p_grapi_30-34.9|p_grapi_35|total_pop|p_race_white|p_race_black|p_race_am_indian|p_race_asian|p_race_nat_hawaiian_pac_islander|p_race_other|p_race_hispanic|
|------|------------------|-----------------|----------------|-------------|------------|--------------------------|-------------|------------------|----------------------------|--------------------------|--------------------|--------------------|------------------|--------------------------|---------------------------|----------|---------------|---------------|---------------|---------------|----------|---------|------------|------------|----------------|------------|--------------------------------|------------|---------------|
|0     |2.49              |8.4              |0               |100          |0           |0                         |39.4         |34                |0                           |26.6                      |                    |17850               |0                 |81.4                      |18.6                       |0         |0              |0              |0              |0              |100       |174      |86.2        |13.8        |0               |0           |0                               |0           |0              |
|1     |2.46              |79.1             |13.4            |99.5         |6.6         |27.7                      |14.2         |24.6              |5.1                         |28.3                      |40724               |56368               |20.7              |68.6                      |31.4                       |21.5      |9.4            |13.7           |16.7           |6              |32.6      |2594     |57.7        |42.5        |0.6             |0           |0                               |0.5         |4.5            |
|2     |2.73              |83.5             |14.6            |99.8         |10.4        |28.4                      |15.6         |32.1              |6.1                         |17.8                      |49077               |61459               |13.2              |77.1                      |22.9                       |23.6      |12.4           |11.5           |1.4            |7.5            |43.5      |4404     |48          |52.7        |0               |0           |0                               |0.2         |0.2            |
|3     |2.14              |85.1             |18.4            |100          |7.7         |21.3                      |18.6         |14.8              |19                          |26.2                      |35250               |47318               |25.8              |67.6                      |32.4                       |22.6      |0              |21.5           |9.7            |0              |46.2      |725      |99.6        |0           |5.5             |0           |0                               |0           |0              |
|4     |2.85              |62.8             |3.1             |100          |22          |5.2                       |35.4         |7.3               |10.4                        |41.7                      |19821               |23781               |41.9              |66.4                      |33.6                       |0         |100            |0              |0              |0              |0         |318      |22          |78          |0               |0           |0                               |0           |0              |


Tail:

|FIELD1|ave_household_size|p_highschool_plus|p_bachelors_plus|p_native_born|p_unemployed|p_occ_business_science_art|p_occ_service|p_occ_sales_office|p_occ_resources_construction|p_occ_production_transport|med_household_income|mean_houshold_income|p_families_poverty|p_household_owner_occupied|p_household_renter_occupied|p_grapi_15|p_grapi_15-19.9|p_grapi_20-24.9|p_grapi_25-29.9|p_grapi_30-34.9|p_grapi_35|total_pop|p_race_white|p_race_black|p_race_am_indian|p_race_asian|p_race_nat_hawaiian_pac_islander|p_race_other|p_race_hispanic|
|------|------------------|-----------------|----------------|-------------|------------|--------------------------|-------------|------------------|----------------------------|--------------------------|--------------------|--------------------|------------------|--------------------------|---------------------------|----------|---------------|---------------|---------------|---------------|----------|---------|------------|------------|----------------|------------|--------------------------------|------------|---------------|
|29562 |                  |                 |                |             |21.8        |4.6                       |43.8         |28.1              |21.3                        |2.2                       |15093               |19981               |57.9              |51.7                      |48.3                       |7.7       |6.7            |27.9           |0              |7.7            |50        |2820     |51.7        |10.4        |0               |5.7         |0                               |34.9        |97.5           |
|29563 |                  |                 |                |             |22.1        |19.7                      |22.1         |21.3              |15                          |21.9                      |22661               |32467               |34.3              |66.8                      |33.2                       |16        |6.7            |2.6            |38.7           |14.4           |21.6      |3544     |85.2        |36.2        |0               |0           |0                               |12          |100            |
|29564 |                  |                 |                |             |24.4        |27.2                      |26.7         |20.3              |4.8                         |21.1                      |14450               |20601               |55.7              |62                        |38                         |3.3       |15.3           |4.8            |2.4            |11.5           |62.7      |6878     |48.5        |46.8        |0.9             |0.3         |0                               |4.9         |99.7           |
|29565 |                  |                 |                |             |18.7        |35.1                      |21.3         |26                |8.1                         |9.6                       |20996               |26865               |33.4              |74.7                      |25.3                       |11.9      |14.9           |11.4           |2.8            |4.5            |54.4      |17129    |84.1        |3.4         |1.3             |0           |0                               |13.4        |99.7           |
|29566 |                  |                 |                |             |7.9         |9.2                       |49.4         |26.4              |0                           |14.9                      |15833               |18462               |61.8              |93.4                      |6.6                        |0         |0              |47.8           |0              |0              |52.2      |1444     |59.4        |28.6        |0               |0           |0                               |14.4        |99.2           |



#### Description:
*GEO_ID*: string
The Census GEO_ID of the place

*NAME*: The census designated name of the place

*ave_household_size*: float
Estimate of the average household size

*p_highschool_plus*: float
Percentage of individuals who have earned a highschool diploma or more

*p_bachelors_plus*: float
Percentage of individuals who have earned a bachelors or beyond

*p_native_born*: float
Percentage of individuals who are native born

*p_unemployed*: float
Percentage of indivuals who are unemployed

*p_occ_business_science_art*: float
Percent of individuals who work a business, science, or art job

*p_occ_service*: float
Percent of individuals who work a service job

*p_occ_sales_office*: float
Percent of individuals who work a sales or office job

*p_occ_resources_construction*: float
Percent of individuals who work a natural resource, construction, or maintenance job

*p_occ_production_transport*: float
Percent of individuals who work a production, or materials transport job

*med_household_income*: float
Estimate of the median household income

*mean_household_income*: float
Estimate of the mean household income

*p_families_poverty*: float
Percentage of families below the poverty line

*p_household_owner_occupied*: float
Percentage of households that are occupied by the owner

*p_household_renter_occupied*: float
Percenatage of households that are occupied by a renter

##### The following fields denote the percentage of people whose Gross Rent as A Percentage of Income (GRAPI)  falls into certain percent ranges

*p_grapi_15*: float
GRAPI <15%

*p_grapi_15-19.9*: float
GRAPI 15.0-19.9%

*p_grapi_20-24.9*: float
GRAPI 20.0-24.9%

*p_grapi_25-29.9*: float
GRAPI 25.0-29.9%

*p_grapi_30-34.9*: float
GRAPI 30.0-34.9%

*p_grapi_35*: float
GRAPI >35.0%

*total_pop*: int
The total population of the place


##### The following represent a what percent of the population is a certain race (includes people of mixed heritage in all relevant categories)

*p_race_white*: float

*p_race_black*: float

*p_race_am_indian*: float

*p_race_asian*: float

*p_race_nat_hawaiian_pac_islander*: float

*p_race_other*: float

*p_race_hispanic*: float

#### Measures of center and dispersion

||count             |mean             |std              |min             |25%               |50%               |75%               |max              |
|------|------------------|-----------------|-----------------|----------------|------------------|------------------|------------------|-----------------|
|ave_household_size|28939.0           |2.5687622239883807|0.5904738173780555|1.08            |2.24              |2.49              |2.79              |19.96            |
|p_highschool_plus|29076.0           |86.50626633649755|11.67166553585477|0.0             |82.0              |89.2              |94.1              |100.0            |
|p_bachelors_plus|29076.0           |21.64855550969869|16.80132174439775|0.0             |10.4              |17.3              |28.2              |100.0            |
|p_native_born|29084.0           |94.3292188144688 |9.18208507401641 |0.0             |93.3              |97.9              |99.8              |100.0            |
|p_unemployed|29175.0           |7.059670951156783|7.4920830425877565|0.0             |2.8               |5.5               |9.1               |100.0            |
|p_occ_business_science_art|29152.0           |30.408098929747666|15.308652877793406|0.0             |20.8              |28.6              |38.1              |100.0            |
|p_occ_service|29152.0           |19.0876166300767 |10.887633989745826|0.0             |13.2              |18.1              |23.5              |100.0            |
|p_occ_sales_office|29152.0           |22.17309961580679|9.829627569360582|0.0             |17.6              |22.4              |26.5              |100.0            |
|p_occ_resources_construction|29152.0           |12.248384330406093|10.032775084419558|0.0             |6.5               |10.3              |15.6              |100.0            |
|p_occ_production_transport|29152.0           |16.084522502744168|11.299802410298724|0.0             |8.4               |14.5              |21.7              |100.0            |
|med_household_income|27493.0           |54076.95449750846|26512.882889745397|3194.0          |37404.0           |48125.0           |62927.0           |248250.0         |
|mean_houshold_income|28684.0           |67710.07697671176|36842.84540492615|2622.0          |47608.0           |58690.5           |75789.75          |722906.0         |
|p_families_poverty|29151.0           |12.223066104078653|12.590069857518978|0.0             |3.5               |9.1               |16.8              |100.0            |
|p_household_owner_occupied|29317.0           |71.16726813794058|17.156540201666267|0.0             |60.9              |72.3              |83.2              |100.0            |
|p_household_renter_occupied|29317.0           |28.833182112767552|17.156504781334256|0.0             |16.8              |27.7              |39.1              |100.0            |
|p_grapi_15|27225.0           |17.6562203856748 |18.747830131157247|0.0             |5.8               |13.2              |23.0              |100.0            |
|p_grapi_15-19.9|27225.0           |13.9278604224058 |15.561408477500066|0.0             |3.3               |11.3              |18.2              |100.0            |
|p_grapi_20-24.9|27225.0           |12.909017447199165|14.810708673048678|0.0             |1.9               |10.8              |17.0              |100.0            |
|p_grapi_25-29.9|27225.0           |11.136907254361681|13.329084584882384|0.0             |0.0               |9.4               |15.0              |100.0            |
|p_grapi_30-34.9|27225.0           |8.61745821854908 |11.79442569707595|0.0             |0.0               |6.6               |11.8              |100.0            |
|p_grapi_35|27225.0           |35.75395041322336|21.94202288786217|0.0             |22.7              |35.7              |46.9              |100.0            |
|total_pop|29567.0           |8166.533398721548|68662.77733759841|0.0             |333.0             |1098.0            |4118.5            |8560072.0        |
|p_race_white|29337.0           |85.73932235743221|21.43122608526757|0.0             |82.6              |95.0              |99.0              |100.0            |
|p_race_black|29337.0           |7.9972355728261455|16.48826193882008|0.0             |0.0               |1.4               |6.6               |100.0            |
|p_race_am_indian|29337.0           |3.8608889797866124|13.35433376465444|0.0             |0.0               |0.6               |2.0               |100.0            |
|p_race_asian|29337.0           |2.3167399529604324|6.048683811021078|0.0             |0.0               |0.3               |2.1               |100.0            |
|p_race_nat_hawaiian_pac_islander|29337.0           |0.3267171149061013|2.647933338579025|0.0             |0.0               |0.0               |0.0               |86.8             |
|p_race_other|29337.0           |2.623008487575417|6.659640091766446|0.0             |0.0               |0.3               |2.2               |100.0            |
|p_race_hispanic|29337.0           |10.818624944609194|20.11168394336868|0.0             |0.3               |3.2               |10.1              |100.0            |
