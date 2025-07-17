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
# Clone the repository
git clone https://github.com/SAKETHVUNKA/metro-user-portal.git
cd metro-user-portal

# Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows
# or
source venv/bin/activate  # On macOS/Linux

# Install project dependencies
pip install -r requirements.txt

# Initialize MySQL database
# 1. Create a new MySQL database (e.g., metro_db)
# 2. Import the provided dump.sql file to populate it:
mysql -u your_mysql_user -p metro_db < dump.sql

# 3. Open the project's utils.py file and update the MySQL connection details:
#    host, user, password, and database name as per your local setup

# Apply Django migrations
python manage.py migrate

# Run the development server
python manage.py runserver
```

## 👥 Authors

 - [Naga Saketh V](https://github.com/SAKETHVUNKA)
 - [Adnan Zaki](https://github.com/zaki-1337)

## 💡 Usage

- Visit http://127.0.0.1:8000/
- Register/login as a user
- Explore schedules, purchase tickets, scan QR codes, and more

## ⚖️ License

This project is open-source and available under the MIT License.