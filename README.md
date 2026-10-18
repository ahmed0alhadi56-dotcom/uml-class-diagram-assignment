# Hotel Booking System - UML Class Diagram Assignment

## Project Overview
This project is part of the UML Class Diagram Modelling Assignment at Kigali Independent University (ULK)[span_0](start_span)[span_0](end_span). It presents a complete object-oriented design for a *Hotel Booking System*.

## Business Idea
An electronic system designed to manage hotel operations, allowing clients to search for available rooms, make bookings, manage guest details, and process payments securely.

## Project Scope
- *Included:* Client profile management, room types and status, booking creation/cancellation, and payment processing.
- *Excluded:* Hotel restaurant management, daily housekeeping services, and staff payroll systems.

## Main Classes & Attributes
1. *Client*: clientId, fullName, email, phone
2. *Room*: roomId, roomType, pricePerNight, isAvailable
3. *Booking*: bookingId, checkInDate, checkOutDate, status
4. *Payment*: paymentId, amount, paymentDate, paymentMethod
