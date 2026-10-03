# Movie Theater Ticket Kiosk

This project represents a simple self-service movie theater kiosk. Customers can view available movies and showtimes, select an available seat, purchase a ticket and receive a confirmation.

The system must also ensure that the same seat cannot be sold to more than one customer.

## Main Features

- View movies and showtimes
- Select available seats
- Purchase tickets
- Receive purchase confirmation
- Prevent duplicate seat sales

## Expanded Use Case: Purchase Ticket

**Primary Actor:** Customer

**Precondition:** The customer has selected a movie and an available showtime.

### Main Steps

1. The customer views the available seats for the selected showtime.
2. The customer selects an available seat.
3. The system verifies that the selected seat is still available.
4. The customer proceeds to purchase the ticket.
5. The system processes the payment.
6. The system creates the ticket for the selected seat and showtime.
7. The system displays a purchase confirmation to the customer.

**Postcondition:** The ticket purchase is recorded, the selected seat is marked as unavailable, and the customer receives confirmation.
