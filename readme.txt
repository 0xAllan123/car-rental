# Car Rental Management System

A web-based car rental management system that allows users to book vehicles and administrators to manage rentals, vehicles, and customer requests.

## Features

- User Authentication (Login/Signup)
- Vehicle Booking System
- Payment Processing
- Admin Dashboard
  - Vehicle Management
  - Booking Approvals
  - Client Request Management
  - Message System

## Technology Stack

- PHP
- MySQL
- HTML/CSS
- JavaScript/jQuery

## Project Structure

```
├── admin/                  # Admin dashboard files
│   ├── add_cars.php       # Add new vehicles
│   ├── approve.php        # Approve bookings
│   ├── client_requests.php # Manage client requests
│   └── ...
├── css/                   # Styling files
├── db/                    # Database files
├── includes/              # Configuration files
├── js/                   # JavaScript files
└── Various PHP files     # Core functionality
```

## Installation

1. Clone this repository to your web server directory
2. Import the database schema from `db/cars.sql`
3. Configure database connection in `includes/config.php`
4. Access the website through your web browser

## Usage

### For Users
1. Create an account or login
2. Browse available vehicles
3. Book a vehicle
4. Make payment
5. Track booking status

### For Administrators
1. Login to admin panel
2. Manage vehicle inventory
3. Process booking requests
4. Handle customer messages
5. View client requests

## Requirements

- PHP 7.0 or higher
- MySQL 5.6 or higher
- Web server (Apache/Nginx)

## License

MIT License

Copyright (c) 2017 Car Rental Management System

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.