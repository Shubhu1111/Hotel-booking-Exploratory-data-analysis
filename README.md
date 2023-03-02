# Hotel-booking-Exploratory-data-analysis
## Introduction
My name is Shubham singh and I am going to analyse the complete data of Hotel booking from 2015 to 2017. In this project I am working on the Hotel Bookings.csv file. This is a very interesting project to work with and the main objective is perform Exploratory Data Analysis on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings 
## Dataset description
Name of the csv file:  Hotel Bookings.csv 
The size of the original dataset:
There were 119390 rows and 32 Columns in this dataset.
### Description about dataset columns:
- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is cancelled or not (0 for no cancelled and 1 for cancelled)
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for Yes)
- previous_cancellations: No. of previous cancelled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or cancelled,or not showed 
- reservation_status_date: Date of making a reservation status.
And i worked on only 15 columns:
## Data wrangling
### Cleaning data
Cleaning data is a crucial step before EDA as it will remove the ambiguous data that can affect the outcome of EDA.
While cleaning data we will perform following steps:
1) Remove duplicate rows
2) Handling missing values.
3) Convert columns to appropriate data types.
4) Adding important columns

### Important libraries

In this exploratory analysis the following libraries has used

Numpy

Pandas

Matplotlib

Seaborn

Plotly

### Following Graphs & plots has used  their descriptions:

Line plot  displays data as points or check marks above a number line, showing the frequency of each value.

Bar plots  should be used when you are showing segments of information. Vertical bar charts are useful to compare different categorical or discrete variables.

Pie plot helps organise and show data as a percentage of a whole. 

Donut plot shows the relationship of parts to a whole, but a donut chart can contain more than one data series.

Countplot is used to represent the occurrence(counts) of the observation present in the categorical variable. 

histogram showing frequency distributions. It is a graph showing the number of observations within each given interval.

### following Different types of Analysis has  done
1) Booking Time Analysis.
2) Revenue Analysis By Months.
3) Booking by different types of Customers Analysis.
4) Market Segment Analysis
5) Special Requests Analysis.
6) Booking Cancellation Analysis.
7) Hotel wise bookings analysis.
8) Preference Analysis.

Useful Insights from EDA.
- July & August have the highest booking count and this will be the right time to give offers and discounts to attract more customers.
- For resort hotels in  July & August have the highest Average Daily rates count and this will be the right time for generating more revenues in these months.
- City hotels have more numbers of Special requests than resort hotels.
- Resort hotels have less cancellations of bookings than city hotels.
- Distribution channel: TA/TO has the highest percentage of cancellations of bookings.
- The Market segment of Online TA has the  highest percentage of cancellations of bookings.
- Transient customer type has the highest percentage of cancellations of bookings.
- Not getting the same room will affect the cancellation percentage.
- Waiting time is one of the major factors affecting the cancellations.
- Portugal has the highest customers and bookings in the world.
- 
And many more useful insights are drawn from this Exploratory data Analysis. 

## Solution to Business Objective.
- Customers reserved  type A rooms so hotels should build these types of rooms in their hotels to reduce waiting period and lead time and raise the booking counts.
- customers preferred BB meals in hotels. Considering this hotels should offer variety of food choices in BB meals for better ratings
- Bookings are more likely to raised in the season of monsoon(July, August, September) hotels should prepare for this season in the following terms
 1-Hotels should reduce lead time.
 2-Hotels should reduce waiting time.
- Arrange more rooms for reservations and bookings in monsoon season especially A type rooms.
- According to the principle of economics, as demand rises prices also rise, so hotels should slightly raise the ADR(average daily rate) for generating more revenue in this season.
- Transient types of customers booked more hotels than others. 
- And Online TA is the dominating market segment in the hotel industry.
- Hotels should make offer and discount policies for these types of customers and market segment.
- City hotels get more Special requests than Resort hotels and  Transient types of customers make more special requests, so city hotels and resort hotels should be ready for special requests by 59.1% and 56.8% respectively.
- City hotels are more prone to cancellation than resort hotels,
Almost 30% of City Hotel bookings got cancelled. One of the main reasons for cancellation is the long waiting period. and not getting the same room as they reserved might be the reason for cancellation.
- Most guests are from Portugal and other European countries. There are more than 50000 people from single country Portugal, hotels should study their tradition and cuisine for better rating and revenues. And this will be done for all European countries. 
