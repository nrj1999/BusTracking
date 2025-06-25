# 🚌 OnRoute – Live Bus Tracking & Booking Made Easy

**OnRoute** is a modern, intuitive web app that lets users track buses live, book tickets, and manage their journey — all from their browser. Designed for simplicity and speed, it simulates the experience of a real bus booking platform.

## 🚀 Features

* 🔐 **Authentication** – Secure signup/login system (Firebase-ready)
* 🧭 **Route Discovery** – View available routes with source and destination
* 🎟️ **Bus Booking** – Book buses and track seat availability
* 📍 **Live Tracking** – Real-time tracking of bus movement on Google Maps
* 🧾 **Ticket Download** – Get a PDF version of your ticket after booking
* ❌ **Cancel Bookings** – Remove previously booked buses
* 📬 *(Coming Soon)* In-app notifications, payment integration
* 🧑‍💼 *(Coming Soon)* Admin dashboard to manage buses & routes

---

## 📸 Screenshots

![Landing](https://github.com/user-attachments/assets/2d0d79e3-9ade-43b5-970c-d914a9b9b14e) |
![Route](https://github.com/user-attachments/assets/8aafb330-8ff9-4950-97e4-1f4973aca686) |
![Bookings](https://github.com/user-attachments/assets/2564ddbf-83ca-40ee-8780-eb6388e036d2) |

---

## 🛠️ Tech Stack

| Category         | Tools Used                 |
| ---------------- | -------------------------- |
| **Frontend**     | React.js, React Router     |
| **UI Framework** | Material-UI (MUI v5)       |
| **Maps**         | Google Maps JavaScript API |
| **Auth Ready**   | Firebase Authentication    |
| **Storage**      | LocalStorage for bookings  |
| **PDF Export**   | jsPDF                      |
| **Deployment**   | Vercel / CodeSandbox       |

---

## 📂 Project Structure

```
src/
├── components/
│   ├── BookingSnackbar.js
│   ├── BusList.js
│   ├── Login.js
│   ├── MapComponent.js
│   ├── MyBookings.js
│   ├── Navbar.js
│   ├── ProtectedRoute.js
│   └── Signup.js
├── App.js
├── index.js
├── index.css
└── styles.css
```

---

## 🔧 Setup & Run Locally

1. **Clone the repository**
 

2. **Install dependencies**
   `npm install`

3. **Start development server**
   `npm start`

4. **Open in browser**
   Visit `http://localhost:3000`

---

## 📦 Deployment

Deployed on **Vercel** with support for live preview. Add your own Google Maps API key.

---

## 💡 Future Enhancements

* 🔔 Push Notifications
* 💳 Stripe-based Payments
* 👨‍💼 Admin Route & Bus Management
* 🔒 Firebase integration for real-time sync



