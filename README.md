# Hotel Bookings
Supervised Learning Binary Classification problem [0,1] by predicting [Hotel Bookings Data](https://www.sciencedirect.com/science/article/pii/S2352340918315191) guests would attend or cancel their reservation. With a final metric of %, this model allows the hospitality industry to find the optimal frontier of services based on attended guests such as food requirements, seasonal patterns, price optimization, availability, employment efficiencies, targeted country marketing, etc. 

<details>
  <summary> Data and Models </summary>
  
  ```
  Binary Targets [0,1]: ['is_canceled']
  Categorical Features:['hotel','arrival_date_month','meal','market_segment','distribution_channel','reserved_room_type','deposit_type','customer_type','country']
  Numerical Features ['lead_time','arrival_date_year','arrival_date_week_number','arrival_date_day_of_month','is_repeated_guest','previous_cancellations','previous_bookings_not_canceled','booking_changes','agent','days_in_waiting_list','adr','required_car_parking_spaces','total_of_special_requests']
  ```
  - Principal Component Analysis: Reduce the dimensionality of the data 
  - Artificial Neural Network:
</details>

## For Stakeholders 
- Percentage of canceled hotel reservations 37%
- Total percentage canceled for Resort and City Hotels:  28% and 42%, respectively 
- Price per Capita: $52
- Top three home country of guests: Portugal (28%), United Kingdom (13%), France (11%) 
- Percentage of canceled hotel based on country: Portugal (63%)
- Monthly High Price for City & Resort Hotels: April-October and July-August, respectively
- Top three Average Daily Rate (ADR) based on month: August ($140), July ($127), June ($117)
- Customer Type that cancels: Groups customertype have a higher cancelation rate over 50%


# Population Segmentation
An unsupervised learning model to seek clusters in the [Population Segmentation Data](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/XTXCYD) and 
[US Census Data](https://data.census.gov/cedsci/) that reveal some sort of demographic traits the define their similarities for different regions (Indexed by concatenating State-County) in the United States. Their similarities will help reveal unseen patterns that help inform campaigns, marketing targets, for a specific cluster. 

<details>
  <summary> Data and Models </summary>

  ```
  Categorical Features:['State','County']
  Integer Features:['TotalPop','Men','Women','Citizen','IncomePerCap','IncomePerCapErr','Employed']
  Float Features:['Hispanic','White','Black','Native','Asian','Pacific','Income','IncomeErr','Poverty','ChildPoverty','Professional','Service','Office','Construction','Production','Drive','Carpool','Transit','Walk','OtherTransp','WorkAtHome','MeanCommute','PrivateWork','PublicWork','SelfEmployed','FamilyWork','Unemployment',]
  ```
  - Principal Component Analysis: Reduce the dimensionality of the data
  - K Means Clustering:
  - Density-Based Spatial Clustering of Applications with Noise (DBSCAN):
</details>


## For Stakeholders 
- Typical county has around 30% Professional Workers
- Top Three Expensive State-County: Virginia-FallsChurch city, New York-New York, Virginia-Arlington
- Top Five Highest Unemployment Rate: Puerto Rico (Adjuntas, Lares, Jayuya, Orocovis, Cataño) also the poorest area
- Top Three Total Population: California-Los Angeles, Illinois-Cook, Texas-Harris
- Top Three employed percentage based on total population: Alaska-Aleutians East Borough, Hawaii-Kalawao, Alaska-Skagway Municipality


# Health Insurance
Explore the [Kaggle Health Insurance Dataset](https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction)
and build two models to predict whether the policyholders (customers) from the previous year will also be interested in Vehicle Insurance provided by the company.

<details>
  <summary> Data and Models </summary>

  ```
  Binary Targets:['Response']  (Customer is interested:1,Customer is not interested:0)
  Categorical Features: ['Gender','Vehicle_Age','Vehicle_Damage']
  Numerical Features ['Age','Driving_License','Previously_Insured','Vintage','Annual_Premium','Policy_Sales_Channel']
  ```
  - XGBoost Classifier
  - Cat Boost Classifier
</details>

## For Stakeholders 
- Percentage of Customers that are Interested: 10.12%
- Customer with their vehicle damaged in the past tend to be interested
- Customer with no Vehicle Insurance tend to be interested
- Vehicle Age of 1-2 years tend to be interested
- Average Age: 39 Years old 
