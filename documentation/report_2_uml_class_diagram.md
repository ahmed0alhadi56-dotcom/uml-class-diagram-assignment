# Report 2: UML Class Diagram Report
## Hotel Booking System Design
- *Classes & Attributes:*
  - Client: clientId, fullName, email, phone
  - Room: roomId, roomType, pricePerNight, isAvailable
  - Booking: bookingId, checkInDate, checkOutDate, status
  - Payment: paymentId, amount, paymentDate, paymentMethod
- *Relationships & Multiplicities:*
  - Client (1) makes Booking (0..*)
  - Booking (1) includes Room (1..*)
  - Booking (1) is associated with Payment (1)
