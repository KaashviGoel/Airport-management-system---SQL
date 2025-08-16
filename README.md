SQL & PL/SQL Highlights

Tables:
Flight, Passenger, Booking, Payment, Airport, Airline with foreign key constraints.

Triggers:
Validate email format.
Restrict invalid payment statuses.
Prevent pending payments from being inserted.
Ensure departure < arrival for flights.
Auto-set payment status when booking is created.

Functions:
generate_boarding_pass(booking_id) → Auto-generate passenger boarding pass.

Procedures:
display_all_flights_today → List today’s flights.
USER_CANCEL(booking_id) → Cancel a booking, update status.
change_time(flight_id, interval) → Adjust flight times dynamically.
