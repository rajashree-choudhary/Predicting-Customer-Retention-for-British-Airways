# Machine learning algorithm designed to forecast which customers will make bookings with British Airways.

## Task
Develop a predictive model utilizing the provided data to determine which customers will book with the airline. Additionally, identify the most significant features crucial for constructing the model.

## Data
The dataset 'customer_booking.csv' includes the training data featuring the target variable 'booking_complete.' A value of 0 indicates that a customer did not complete booking, while a value of 1 signifies completion of booking.

To provide more context, below is a more detailed data description, explaining exactly what each column means:

- `num_passengers` = number of passengers travelling
- `sales_channel` = sales channel booking was made on
- `trip_type` = trip Type (Round Trip, One Way, Circle Trip)
- `purchase_lead` = number of days between travel date and booking date
- `length_of_stay` = number of days spent at destination
- `flight_hour` = hour of flight departure
- `flight_day` = day of week of flight departure
- `route` = origin -> destination flight route
- `booking_origin` = country from where booking was made
- `wants_extra_baggage` = if the customer wanted extra baggage in the booking
- `wants_preferred_seat` = if the customer wanted a preferred seat in the booking
- `wants_in_flight_meals` = if the customer wanted in-flight meals in the booking
- `flight_duration` = total duration of flight (in hours)
- `booking_complete` = flag indicating if the customer completed the booking

## Feature Importances


The primary factors influencing booking decisions include the duration of the flight, the length of stay at the destination, and the desire for additional baggage. Flight duration, indicating how long a flight lasts, plays a crucial role in a customer's decision to book with the airline. Similarly, the length of stay at the destination also impacts the likelihood of booking. Furthermore, the option to include extra baggage significantly influences customers' booking choices.
