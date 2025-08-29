# 📊 Airbnb Clone Backend – Use Case Diagram

## 📌 Overview
This directory contains the **Use Case Diagram** for the **Airbnb Clone Backend** project.  
The diagram provides a visual representation of the interactions between different **actors** (users, hosts, admins, and guests) and the **system**.  

It illustrates the **functionalities** supported by the backend such as:
- User registration and authentication
- Property management
- Booking system
- Payments
- Reviews
- Admin monitoring and control

---

## 🎭 Actors
The main actors in the system are:

1. **User**  
   - A general entity that can act as a Guest or Host.

2. **Guest**  
   - Registers/logs in.  
   - Searches properties.  
   - Books properties.  
   - Makes payments.  
   - Writes reviews.  

3. **Host**  
   - Manages property listings (add, edit, delete).  
   - Views bookings.  
   - Responds to reviews.  

4. **Admin**  
   - Monitors transactions.  
   - Oversees listings.  
   - Manages users.  
   - Generates reports.  

5. **System**  
   - Core backend that handles requests, processes data, and integrates all functionalities.  

---

## ⚙️ Key Functionalities (Use Cases)
- **User Registration & Login** – Secure signup/login with authentication.  
- **Search Properties** – Guests search for listings by filters.  
- **Book Property** – Guests book available properties.  
- **Make Payment** – Guests pay via integrated gateways.  
- **Write Review** – Guests review properties after stays.  
- **Manage Listings** – Hosts add, edit, or remove property listings.  
- **View Bookings** – Hosts track bookings for their listings.  
- **Respond to Reviews** – Hosts reply to guest reviews.  
- **Monitor Transactions** – Admins oversee all financial activity.  
- **Oversee Listings** – Admins manage property listings.  
- **Generate Reports** – Admins generate system-wide reports.  
- **Manage Users** – Admins create, update, or remove users.  

---

## 🖼️ Diagram
The use case diagram is shown below:

![Use Case Diagram](./Usecase%20diagram.png)

---

## 📂 Repository Structure
```bash
alx-airbnb-project-documentation/
│── use-case-diagram/
│   ├── Usecase diagram.png
│   └── README.md
