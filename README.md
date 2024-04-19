# Water Park Tour Management System

The Water Park Tour Management System is a program designed to streamline the management of various activities during a visit to a water park. Users can register, login, and access features such as buying tickets, ordering food, renting lockers, purchasing souvenirs, selecting attractions, parking, processing payments, and providing feedback.

## Features

### Registration and Login

- Users can register their username and password to create an account.
- The `Person` class handles registration and login functionalities.
- After successful registration, users can log in to access the system.

### Ticket Management

- Users can buy tickets of different types: Basic, Standard, and Premium.
- The `Ticket` class manages ticket-related operations such as setting the ticket type and cost, which is determined based on the selected type.

### Food Ordering

- Users can order food from available options based on their ticket type.
- The `Food` class handles food ordering and calculates the cost accordingly.

### Locker Rental

- Users can rent lockers by adding the rental cost to their bill.
- The `Locker` class manages the locker rental process and verifies the user's credentials.

### Souvenir Purchase

- Users can purchase souvenirs such as caps, shirts, and accessories.
- The `Souvenir` class handles the selection of the souvenir type and calculates the cost accordingly.

### Attraction Selection

- Users can select attractions based on their ticket type.
- The `Attraction` class manages the attraction selection process and calculates the cost accordingly.

### Parking Management

- Users can park their vehicles in different parking areas based on their ticket type.
- The `Parking` class handles parking-related operations and calculates the cost accordingly.

### Bill Display

- Users can view their bill, which includes the costs of tickets, food, locker rental, souvenirs, attractions, and parking.
- The `display_All` class calculates and displays the total cost.

### Payment Processing

- Users can choose a payment method (credit card, cash, or bank transfer) and process the payment.
- The `display_All` class handles payment processing and displays the payment method and total cost.

### Feedback

- Users can provide feedback about their experience at the water park.
- The `Feedback` class allows users to give feedback, which is stored in a file.

## Conclusion

The Water Park Tour Management System provides a comprehensive set of features for managing various activities during a visit to a water park. Users can easily register, purchase tickets, order food, rent lockers, buy souvenirs, select attractions, park their vehicles, view their bill, process payments, and provide feedback. The program simplifies the management of water park operations and enhances the overall visitor experience.
