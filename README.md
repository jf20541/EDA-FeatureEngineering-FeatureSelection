# ExploratoryDataAnalysis

## Hotel Bookings
[Hotel Bookings Data Link](https://www.sciencedirect.com/science/article/pii/S2352340918315191)
```bash
Binary Targets [0,1]: ['is_canceled']
Categorical Features:['hotel','arrival_date_month','meal','market_segment','distribution_channel','reserved_room_type','deposit_type','customer_type','country']
Numerical Features ['lead_time','arrival_date_year','arrival_date_week_number','arrival_date_day_of_month','is_repeated_guest','previous_cancellations','previous_bookings_not_canceled','booking_changes','agent','days_in_waiting_list','adr','required_car_parking_spaces','total_of_special_requests']
```
### Objective
Binary Classification problem [0,1] by predicting if a hotel guest will attend or cancel their reservation. With a final metric of %, this model allows the hospitality industry to find the optimal frontier of services based on attended guests such as food requirements, seasonal patterns, price optimization, availability, employment efficiencies, targeted country marketing, etc. 

### Simple Model and Complex Model 
- Logistic Regression:
- Artificial Neural Network:

### For Stakeholders 
- Percentage of canceled hotel reservations 37.04%
- Total percentage canceled for Resort and City Hotels:  27.76% and 41.73%, respectively 
- Price per Capita: $51.74
- Top three home country of guests: Portugal (28%), United Kingdom (13%), France (11%) 
- Percentage of canceled hotel based on country: Portugal (63%)
- Monthly High Price for City & Resort Hotels: April-October and July-August, respectively
- Top three Average Daily Rate (ADR) based on month: August ($140), July ($127), June ($117)
- Customer Type that cancels: Groups customertype have a higher cancelation rate over 50%


## Population Segmentation

