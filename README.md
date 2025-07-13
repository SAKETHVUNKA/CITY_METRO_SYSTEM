# CITY_METRO_SYSTEM

A full-stack web application to manage and serve all data and services related to a city's metro system, designed for general metro users.

## 🚇 Features

- Buy and scan metro tickets (QR code-based)
- Buy and scan parking receipts (QR code-based)
- View detailed station information (platforms, visitor data, etc.)
- Check live and historical rider data (per station, daily, live count)
- View metro schedule (arrival time, expected duration, price)
- Find travel time, distance, and cost between stations
- User registration and login
- Personalized metro card:
  - Recharge (top-up)
  - Track usage and trips
  - Get offers and savings
- Manage parking linked to user accounts and vehicles

## 💾 Database

- **Database:** MySQL
- **Main tables:**
  - User
  - Rider_Card
  - Tickets
  - Parking
  - Schedule
  - Station
  - Line
  - Route

## 🧩 Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS
- **Database:** MySQL

## 🏗️ Setup

```bash
# Clone the repository
git clone https://github.com/SAKETHVUNKA/metro-user-portal.git
cd CITY_METRO_SYSTEM

# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows
# or
source venv/bin/activate  # On macOS/Linux

# Install dependencies
pip install -r requirements.txt

# Configure your MySQL database in settings.py

# Apply migrations
python manage.py migrate

# Run the server
python manage.py runserver
```

## 💡 Usage

- Visit http://127.0.0.1:8000/
- Register/login as a user
- Explore schedules, purchase tickets, scan QR codes, and more

## ⚖️ License

This project is open-source and available under the MIT License.
