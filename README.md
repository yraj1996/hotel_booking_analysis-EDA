# Hotel Booking Anaysis-EDA
![STAAH-guests-at-hotel-reception-check-in](https://user-images.githubusercontent.com/109631137/180631271-b3d87a4a-ccd3-46d7-8007-b1d70da65c22.png)
## objective
We are provided with a hotel bookings dataset.

Our objective is to perfrom Exploratory Data Analysis(EDA) and need to find some useful insights,trends and conclusion in Hotel Bokings.
## Dataset
We have a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following coloumns:

- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- lead_time: the number of days between the time a guest books their room and the time they are scheduled to arrive at the hotel.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date.
- stays_in_weekend_nights: No. of weekend nights spent in a hotel.
- stays_in_week_nights: No. of weeknights spent in a hotel.
- adults: No. of adults.
- children: No. of children.
- babies: No. of babies.
- meal: Type of meal chosen 
- country: origin  country of customers.
- market_segment: What segment via booking was made.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Repeat Guests are those who tend to stay in the same hotel regularly.(0 for No and 1 for Yes)
- previous_cancellations: No. of previous canceled bookings.
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
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.

1. Total number of rows in data: 119390
2. Total number of columns: 32

## Understanding,Wrangling and Cleaning the Data. 
- step 1: Data cleaning by looking out and handling the missing values and replace those with integers.
- step 2: All duplicate rows were dropped.
- step 3: replacing null values.
- step 4: dropping columns that are not significant for our future data exploration and predictions.
- step 5: Converting columns to appropriate data types.
## Creating new columns for further analysis.
* creating some new columns for our dataset which helps us in future data exploration and predictions.

## Exploratory Data Analysis and Visualization.
Performed EDA and tried answering the following questions:
1. Visualizing Hotel wise yearly bookings
2. From which country the most guests are booking hotel ?
3. Visualizing market segments wise bookings.
4. Distribution channel wise bookings.
5. which customer type making most of bookings?
6. Visualizing percentage of monthly cancellation by customer_type.
7. visualizing monthly bookings.
8. Let's try to analyse the total no of cancelation made in each month.
9. no. of cancellation in each type of hotel.
10. Which meal type is most preffered meal by customers?
11. What is realtionship between ADR and total stay of guests?
12. Relationship between 'not getting prefered room' and 'booking cancellation'?
13. Relationship between room allotment and adr.
14. Find any positive and negative impact of relationship between lead time and bookings?
15. What kind of realtionship between Hotel price and arriving months?
16. overall correlation between the numerical data.
## Conclusion
1. Around 60% bookings are for City hotel and 40% bookings are for Resort hotel.But there is also more no of cancellation in City Hotel in comaprison to Resort Hotel.
2. Most of visitors are from Portugal,France, Great Britain, and Spain.
3. Bookings through online and offline travel agents are higher.
4. The travel agents whether online/offline have the highest distribution rates.
5. Transient type customer make more bookings in comaprison to others and there cancellation rate is also higher.
6. Not getting same room as reserved, longer lead time and waiting time do not affect cancellation of bookings.
7. May,October and april are most busiest month as most no of guest arrive in these months.
8. Most preferred meal type among customers is BB (Bed and breakfast).
9. Resort Hotels are more expensive than City Hotels. Resort hotels prices also see some up and down during peak and off season where as City hotels maintain a constant price with little ups and downs.
10. The more lead time leads to less number of cancellation. It shows the customers who make thier plans in advance are highly unlikely to cancel their booking.
11. customers who didn't get preferred room, they pay slightly less money that means different room allotment do lowers the adr.
12. There is no impact on bookings cancellation even after customers are not getting preferred rooms.
13. As customers stays increase their is slight decrease in adr.

## From this EDA project, the following concepts were learnt:
- Basic inspection of the raw data with the use of python and it's libraries.
- Examining the business KPIs for understanding and finding the solutions for some question which may helps in business growth.
- Handing the duplicate, error and NaN values present in the dataset, i.e., cleaning the data.
- Using different Python functions and libraries to clean and manipulate data.
- creating multiple visualizations for better understanding relationship between data and its impact on hotel booking. Visualization also helps us in finding some optimal solutons of business problems.
