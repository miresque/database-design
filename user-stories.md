# Epic

"A local cinema wants to allow people to book tickets online to see movies that are being shown in its various screens. These tickets should be delivered to customers via email. The cinema wants to keep a record of their customers and the tickets they purchase, as well as offer a regularly updated list of movies for them to choose from. A single screen might show multiple movies a day, and even the same movie at multiple times. The cinema will expand its number of screens in the future, so the potential for growth needs to be accounted for."

## User Stories

### Customers

- As a customer, so I can decide which movie I want to watch, I want to see a list of movies.
- As a customer, so I can watch a movie by myself or with other people, I want to be able to purchase one or more tickets.
- As a customer, so I can receive my tickets, I want to provide my contact information.
- As a customer, so I can know where the movie is playing, I want to be able to see which cinema it is playing in and which screen.

### Admin

- As an admin, so I can manage the movies shown at the cinema, I want to update the list of movies.
- As an admin, so I can record the amount of tickets bought by customers, I want to be able to record all the customers and their purchased tickets.
- As an admin, so I can manage the viewings for each screen, I want to be able to update the list of screens, their showings and the time of those showings.
- As an admin so I can manage the scaling/growth of the cinema, I want to be able to update the list of screens available.

## Entities

- Movie: Title, Director, Release Year, Runtime, Age Rating
- User: Username, Password, Role
- Contact: Name, Phone Number, Email, User ID
- Ticket: Title, Type, Screen, Seat, Rating, Start Time, Date, Price
- Screen: Max Seats, Availability
- Cinema: Name, Address
- Booking: User ID, Ticket ID
