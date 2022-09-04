# Priyadarshani17/Hotel-Booking-analysis
1.Problem Statement :

We have been provided with hotel booking data for three years. We have to analyze the hotel booking behavior of customers as well as discover important factors that govern the bookings. We will analyze some important aspects of hotel bookings which will help us identify major loopholes and give us insights which will be helpful to run a profitable hotel business.

2. Introduction : 
This is our capstone project on exploratory data analysis on hotel booking in which we solved different questions like the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? Etc. This hotel booking dataset can help you explore those questions!
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, meal perferance, among other things. 
The main objective of this project is to explore and analyze data to discover important factors that governs the bookings and give insights to hotel management, which can perform various campaigns to boots the business and performance.
. Data Description :
●	hotel: Name of hotel ( City or Resort)
●	is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
●	lead_time: time (in days) between booking transaction and actual arrival.
●	arrival_date_year: Year of arrival
●	arrival_date_month: month of arrival
●	arrival_date_week_number: week number of arrival date.
●	arrival_date_day_of_month: Day of month of arrival date
●	stays_in_weekend_nights: No. of weekend nights spent in a hotel
●	stays_in_week_nights: No. of weeknights spent in a hotel
●	adults: No. of adults in single booking record.
●	children: No. of children in single booking record.
●	babies: No. of babies in single booking record.
●	meal: Type of meal chosen
●	country: Country of origin of customers (as mentioned by them)
●	market_segment: What segment via booking was made and for what purpose.
●	distribution_channel: Via which medium booking was made.
●	is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for Yes)
●	previous_cancellations: No. of previous canceled bookings.
●	previous_bookings_not_canceled: No. of previous non-canceled bookings.
●	reserved_room_type: Room type reserved by a customer.
●	assigned_room_type: Room type assigned to the customer.
●	booking_changes: No. of booking changes done by customers
●	deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
●	agent: Id of agent for booking
●	company: Id of the company making a booking
●	days_in_waiting_list: No. of days on waiting list.
●	customer_type: Type of customer(Transient, Group, etc.)
●	adr: Average Daily rate.
●	required_car_parking_spaces: No. of car parking asked in booking
●	total_of_special_requests: total no. of special request.
●	reservation_status: Whether a customer has checked out or canceled,or not showed
●	reservation_status_date: Date of making reservation status.
Steps Followed In Analysis
Data collection : We collected  the hotel booking data on which EDA is to be done. We then understood the data, its columns/features and its content.

Data cleaning : We cleaned the data by dropping or replacing null values, deleting unwanted columns, checking data type and conversion to a data type of required column and we performed many other operations to get the required dataset
EDA will be divided into following 3 analysis:
1)Univariate Analysis: Univariate analysis is the simplest of the three analysis where the data you are analyzing is only having one variable.
2)Bivariate analysis: In Bivariate analysis we will compare two variables to study their relationships.
3)Multivariate analysis: Multivariate analysis is similar to Bivariate analysis here we will compare more than two variables.
Data visualization: We represented the insights through data visualization with the help of different types of graphs and charts.
 Conclusion: After careful analysis , we can conclude that the hotel industry can benefit a lot by studying the type of customers, their booking mode, the booking month and the seasons. The hotel industry market, their ADR and bookings are based on the type of customers, the month, types of meal, hotel type, their country of origin, Room types, booking medium and many others. Form this analysis 

