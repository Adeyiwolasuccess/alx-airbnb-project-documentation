# 📝 User Stories – Airbnb Clone Backend

## 📌 Overview
This document contains **five core user stories** derived from the Use Case Diagram of the Airbnb Clone Backend project.  
Each story captures a **specific user goal**, the **actions they want to perform**, and the **value** it provides.

---

## 🎭 User Stories

### 1. User Registration
- **As a new user**, I want to create an account with my email and password so that I can access the platform as either a guest or a host.  
- **Acceptance Criteria:**
  - Users must provide a valid email, password, and role (guest or host).
  - Duplicate emails should not be allowed.
  - Registration confirmation should be sent via email.

---

### 2. Login & Authentication
- **As a registered user**, I want to log into the system securely so that I can manage my bookings (as a guest) or my property listings (as a host).  
- **Acceptance Criteria:**
  - Login requires valid credentials (email + password).
  - Invalid credentials should return an error message.
  - Successful login should return a secure session (JWT).

---

### 3. Property Listing
- **As a host**, I want to add and manage property listings with details such as location, price, amenities, and availability so that guests can find and book my properties.  
- **Acceptance Criteria:**
  - Hosts can create, update, and delete their own listings.
  - Listings must include required details: title, description, location, price, and at least one image.
  - Listings should become visible to guests immediately after creation.

---

### 4. Property Search & Booking
- **As a guest**, I want to search for properties by location, price, and availability so that I can find suitable accommodation and make a booking.  
- **Acceptance Criteria:**
  - Guests can filter search results by location, price, and amenities.
  - Booking should only be possible for available dates (no double bookings).
  - Successful booking should trigger a confirmation notification.

---

### 5. Payments
- **As a guest**, I want to make secure payments for my bookings so that my reservation is confirmed and the host is guaranteed payment.  
- **Acceptance Criteria:**
  - Payments must be processed via a secure gateway (e.g., Stripe, PayPal).
  - The system should support multiple currencies.
  - Hosts should receive payouts automatically after booking completion.

---

## ✅ Summary
These five user stories represent the **most critical interactions** of the Airbnb Clone Backend, ensuring the platform supports secure access, property management, booking, and payments.
