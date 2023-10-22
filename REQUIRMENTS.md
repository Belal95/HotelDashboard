# Business requirements

A dashboard for hotel employees to mange rooms, add guests information and update there booking status

## Users

- Only user is hotel employee

## Data

- Users [photo, name, password]
- Rooms [photo, name, capacity, price, discount]
- Bookings [arrive_date, depurate_date, status(unconfirmed, checkedIn, checkout), paid_amount, guest_number, price, night_numbers, with_breakfast, cabin & guest data]
- Guests [full_name, email, national_ID, nationality, ]

## Features

### User

- User login
- No sign up
- User can change avatar, name, password

### Rooms

- CRUD operations
- Upload photo
- Filter (Name, price, discount, capacity)

### Bookings

- Create booking
- Change from unconfirmed to checkIn to checkOut
- Delete unconfirmed booking
- Change paid amount
- Change Breakfast
- Filter (Date, status)

### Guests

- CRU Operations
- Filter

### Global settings

- Breakfast Price
- Min/Max nights per booking
- Max Guests per booking

### Reports

- Daily sales
- Average stay duration
- Occupancy rate
