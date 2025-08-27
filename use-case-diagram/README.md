# Airbnb Clone – Use Case Model
## 🎭 Actors

User

Guest (inherits from User)

Host (inherits from User)

Admin

## 👤 User Management

Register/Login (Guest, Host)

«include» → Authenticate

Manage Profile (Guest, Host)

View Users (Admin)

## 🏡 Property Management

Add Listing (Host)

Edit Listing (Host)

Delete Listing (Host)

Search & Filter Listings (Guest)

## 📅 Booking Management

Create Booking (Guest)

«include» → Notifications

Cancel Booking (Guest)

«include» → Notifications

Track Booking Status (Guest, Host)

## 💳 Payments

Make Payment (Guest)

«include» → Notifications

«extend» → Receive Payout

Receive Payout (Host)

## ⭐ Reviews

Write Review (Guest)

«extend» → Respond to Review

Respond to Review (Host)

## 🔔 Notifications

Notifications (Email/In-app) (Guest, Host)

Triggered by:

Create Booking («include»)

Cancel Booking («include»)

Make Payment («include»)

## 🛠️ Admin

Manage Users (Admin)

Manage Listings (Admin)

Manage Bookings (Admin)

Manage Payments (Admin)
