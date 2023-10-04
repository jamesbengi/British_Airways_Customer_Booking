# Machine Learning Model to predict which customer books with British Airways
#Task
Build a model that predicts which customer books with the airline using the data provided
To find out what are the most important features for building the model
#Data
The file 'customer_booking.csv' contains the training data with the target variable 'booking_complete' which indicates 0 for a customer that did not complete booking and 1 for those that copleted booking.

To provide more context, below is a more detailed data description, explaining exactly what each column means:

num_passengers = number of passengers travelling
sales_channel = sales channel booking was made on
trip_type = trip Type (Round Trip, One Way, Circle Trip)
purchase_lead = number of days between travel date and booking date
length_of_stay = number of days spent at destination
flight_hour = hour of flight departure
flight_day = day of week of flight departure
route = origin -> destination flight route
booking_origin = country from where booking was made
wants_extra_baggage = if the customer wanted extra baggage in the booking
wants_preferred_seat = if the customer wanted a preferred seat in the booking
wants_in_flight_meals = if the customer wanted in-flight meals in the booking
flight_duration = total duration of flight (in hours)
booking_complete = flag indicating if the customer completed the booking
#Feature Importances
![Alt image](visualizatio/BA.png)
The most important variable in the model was purchase_lead, 
that is the time between purchase and departure
Length of stay also plays a key role in determining if a customer will 
Complete the booking



