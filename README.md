# SJSU Bus Application

## Project Overview
The SJSU Bus Application is a bus ticketing and tracking system designed for San José State University (SJSU). It streamlines bus route management, ticket booking, and real-time bus tracking for students, faculty, and staff.

## Key Features
- User Authentication for secure login and registration
- Bus Ticket Booking and management
- Real-Time Bus Tracking
- Admin functionality for managing routes and schedules
- Notifications for bus delays and updates

## Tech Stack
- Backend: Python, Django REST Framework
- Frontend: HTML, CSS, JavaScript
- Database: SQLite (development), PostgreSQL (production)
- APIs: Google Maps API

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/pushkar4844/SJSU-BUS-Application.git
   cd SJSU-BUS-Application
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Apply migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```
4. Run the server:
   ```bash
   python manage.py runserver
   ```

## Usage
1. Register or log in to the system.
2. Search for bus routes and book tickets.
3. Track buses in real-time.
4. Admins can manage routes and schedules.

## Future Enhancements
- Payment Gateway Integration
- Advanced Search Filters
- Admin Dashboard
- Mobile App Development

## Contributing
1. Fork the repository.
2. Create a new branch (`feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License.

## Contact
Pushkar Patil  
Email: pushkar4844@gmail.com  
GitHub: [pushkar4844](https://github.com/pushkar4844)

Let's make campus transport smarter and more efficient.

