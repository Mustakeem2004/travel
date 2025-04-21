# 🌍 Travel Booking System

This is a simple hotel booking management system built with PHP, MySQL, and phpMyAdmin. It allows users to browse hotels, make bookings, and store data in a MySQL database.

---

## 📁 Project Structure

```
travel/
├── database/
│   └── travel.sql       # SQL dump of the travel database
├── index.html / .php    # Your frontend/backend files
├── css/                 # Stylesheets
├── js/                  # JavaScript (if any)
└── README.md
```

---

## 🛠️ Features

- View hotel listings
- Book a hotel
- Store booking info in MySQL
- Admin view of bookings via phpMyAdmin

---

## 🧑‍💻 Technologies Used

- PHP
- MySQL
- phpMyAdmin
- HTML/CSS/JavaScript

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Mustakeem2004/travel.git
cd travel
```

### 2. Import the Database

1. Open **phpMyAdmin**
2. Create a new database named `travel`
3. Click the `Import` tab
4. Upload `database/travel.sql`
5. Click **Go**

### 3. Run the Project

- Place the project in your server directory (e.g., `htdocs` for XAMPP)
- Visit `http://localhost/travel/`

---

## 📷 Database Schema Overview

### Table: `book`

| Column        | Description                     |
|---------------|---------------------------------|
| `id`          | Booking ID                      |
| `hotelID`     | Foreign key to hotel            |
| `hotelName`   | Name of the hotel               |
| `startDate`   | Booking start date              |
| `endDate`     | Booking end date                |
| `userID`      | ID of the user                  |
| `price`       | Booking price                   |
| `peopleValue` | Number of people                |
| `nights`      | Number of nights                |
| `discount`    | Discount applied                |
| `bookingName` | Name of the person booking      |
| `bookingEmail`| Email address                   |
| `bookingPhone`| Phone number                    |
| `create_at`   | Time of booking                 |

---

## 🙋‍♂️ Author

- **Mustakeem Malik**
- GitHub: [@Mustakeem2004](https://github.com/Mustakeem2004)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

