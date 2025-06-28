# 🌟 Airbnb Clone Backend – Features and Functionalities

This document outlines the essential backend features required for the Airbnb Clone project. These features enable guests, hosts, and administrators to interact with the system through secure, scalable, and efficient endpoints.

---

## 🔐 1. User Authentication and Authorization
- Register as guest or host
- Login with email and password
- OAuth support (Google, Facebook)
- JWT-based session management
- Role-based access control (guest, host, admin)

---

## 🏠 2. Property Listings Management
- Add new listings with:
  - Title
  - Description
  - Location
  - Price per night
  - Images
  - Amenities
- Edit or delete listings (host only)
- View all listings
- View single listing by ID

---

## 🔍 3. Search and Filtering
- Search by:
  - Location
  - Price range
  - Guest capacity
  - Amenities
- Paginated results for performance

---

## 📅 4. Booking System
- Book property with check-in and check-out dates
- Prevent overlapping bookings
- Cancel a booking
- View booking status:
  - `pending`, `confirmed`, `cancelled`, `completed`

---

## 💳 5. Payment Integration
- Secure payment gateway (e.g., Stripe, PayPal)
- Guest payments for bookings
- Host payouts after completion
- Support multiple currencies

---

## 🌟 6. Reviews and Ratings
- Guests can leave reviews after a booking
- Hosts can respond to reviews
- Display average rating per property

---

## 🔔 7. Notification System
- Email and in-app alerts for:
  - Booking confirmations
  - Cancellations
  - Payments

---

## 🛠 8. Admin Dashboard
- Admins can:
  - Manage users
  - View/edit/delete listings
  - Monitor payments and bookings

---

## 📎 Feature Overview Diagram
Please refer to `features-and-functionalities.png` in this folder for a visual map of all core features and responsibilities.

