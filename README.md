# Porsche_Hackathon
Runner up project of the 2019 Porsche Hackathon in Atlanta. Organized by Atalytics. Total 35 teams participated in this contest with members consisting of leading Data scientist from various major corporations across Atlanta. 

There were 3 questions and we took a novel approach for answering each questing using Data-driven methodologies. 

This can be a good case study for aspiring Data scientist. 

# 1) Where to build which charging stations and why?

## We ran a real world simulation using Python's sympy library.
* Input features - Number of Chargers at Zip code, Type of chargers and their charging time, Average car arrival rate, Population of the zip code.
* Output - Expected Average waiting time at each zip code.

## Data sources - https://afdc.energy.gov/fuels/electricity_locations.html#/find/nearest?fuel=ELEC

### first slide over here

# 2)  Which customers are likely to buy which EV's, which ones aren't?
* We focused on the state of california.
* Data augmented from multiple sources - US CENSUS DATA, CALIFORNIA DMV DATA, SCRAPED PRICES OF MAJOR CAR BRANDS.
### Features - Each row aggregated at the level of zip code
* CAR PRICES BY DIFFERENT FUEL TYPES
* SEX RATIO
* POPULATION AT THE ZIP CODE BY EDUCATION LEVEL
* POPULATION AT THE ZIP CODE BY DIFFERENT TYPE OF HOME OWNERSHIP
* HOUSING TYPES AND PRICES

### Methodology - 
* K-means clustering over all the features got nice five clusters. All the clusters converted into personas for marketing.


## Output - 

### second slide over here

# 3) Who should we market to, what kind of cars and where?

* We answered both the first and third question over here.
* We selected the cluster we wanted to target for this car, selected all the zip codes of this cluster.
* All this zip codes were accordingly given heavier weights for installing EV CHARGERS.
* Likewise we selected the 2nd and 3rd cluster.

### Output - 

### Third slide over here

* The cluster's that have to be marketed for this car or car of any prices can be selected upon by the business requirement.
