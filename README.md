# Machine Learning Model to predict which customer books with British Airways<br>
# Task
Build a model that predicts which customer books with the airline using the data provided<br>
To find out what are the most important features for building the model<br>
# Data<br>
The file 'customer_booking.csv' contains the training data with the target variable 'booking_complete' which indicates 0 for a <br>
customer that did not complete booking and 1 for those that copleted booking.<br>

To provide more context, below is a more detailed data description, explaining exactly what each column means:<br>

<li>num_passengers = number of passengers travelling<br>
<li>sales_channel = sales channel booking was made on<br>
<li>trip_type = trip Type (Round Trip, One Way, Circle Trip)<br>
<li>purchase_lead = number of days between travel date and booking date<br>
<li>length_of_stay = number of days spent at destination<br>
<li>flight_hour = hour of flight departure<br>
<li>flight_day = day of week of flight departure<br>
<li>route = origin -> destination flight route<br>
<li>booking_origin = country from where booking was made<br>
<li>wants_extra_baggage = if the customer wanted extra baggage in the booking<br>
<li>wants_preferred_seat = if the customer wanted a preferred seat in the booking<br>
<li>wants_in_flight_meals = if the customer wanted in-flight meals in the booking<br>
<li>flight_duration = total duration of flight (in hours)<br>
<li>booking_complete = flag indicating if the customer completed the booking<br>
# Feature Importances<br>
![image](https://github.com/jamesbengi/British_Airways_Customer_Booking/blob/master/visualization/BA.png)<br>
The most important variable in the model was purchase_lead, <br>
that is the time between purchase and departure<br>
Length of stay also plays a key role in determining if a customer will <br>
Complete the booking<br>



