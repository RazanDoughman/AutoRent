# Auto Rent – Your Online Car Rental Platform

A full-stack web application for renting cars online. Auto Rent allows users to browse cars, make reservations, pay online, and manage bookings through a modern, responsive interface.

>  **Full Report:** See `Report.docx` in the repo  
>  **Demo Video:** [Watch on Google Drive](https://drive.google.com/file/d/1tEJnKX-lcjQke_EdGVC61-zzFtksCI8X/view?usp=sharing)

---

##  Key Features

### User Features
- Secure registration and login (JWT-based authentication)
- Car browsing by group, filters (fuel type, seats, etc.)
- Online reservation with:
  - Pickup/drop-off selection
  - Date/time scheduling
  - Additional services (chauffeur, baby seat, insurance, fuel)
- Online payment system with discount coupons
- Points system for user discounts
- Invoice generation
- Review system and live chat with agents
- Mobile-friendly responsive design

### Admin Features
- Manage cars, car groups, users, and reservations
- Invoice generation
- Dashboard statistics
- Secure authentication with role-based access

---

## Tech Stack

| Layer         | Technology           |
|--------------|----------------------|
| Frontend     | HTML, CSS, JavaScript |
| Backend      | Node.js, Express.js   |
| Database     | MongoDB (via Mongoose) |
| Auth         | JWT (JSON Web Tokens) |
| File Uploads | Multer               |
| Maps         | Google Maps API      |

---

## REST API Overview

- `/users` – User registration, login, management
- `/cars` – Car listing, filtering
- `/reservations` – Reservation management
- `/invoices` – Invoice generation

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/auto-rent.git

# Navigate into project directories
cd auto-rent

# Install dependencies
npm install

# Start the server
npm start
```
---

## Team

- **Razan Doughman** – Database & backend, frontend support (razan.doughman@gmail.com)
- **Batoul Ballout** – Backend & integrations, frontend support (batoulballout96@gmail.com)
- **Rasha Harb** – Frontend & UI design, backend support (rashah.harb@gmail.com)


---
