# CakePHP Project: Booking System & Admin dashboard
> **Note:** Due to confidentiality agreements, the source code is not publicly available.  
> This repository serves as a **project overview** to showcase my work on a real-world PHP application.

## 📌 Project Overview
This project involved developing a **fully customised booking system** and **admin dashboard** from scratch for a **pram cleaning business**. The project was developed following **Agile methodologies**, enabling continuous collaboration with the client and quick adaptation to changing requirements.  

The client’s previous booking solution, built on WordPress, had several restrictions that limited their ability to provide accurate information and options, and track service progress. My goal was to create a tailored system that **solved these pain points** while improving operational efficiency.

## 🎯 Objectives
- **Replace WordPress limitations** with a scalable, flexible booking solution.
- **Automate and streamline** the entire booking-to-payment process.
- Provide an **admin dashboard** for:
  - Managing services and store branches.
  - Monitoring staff tasks and progress.
  - Updating booking statuses in real time.
- Ensure **real-time synchronisation** between customer bookings and admin management to avoid time slot collisions.
- Enhance user experience with **secure payment integration** and **location mapping**.

## 🎯 My Role
- Developed frontend AND backend features in **PHP (CakePHP Framework)**.
- Integrated third-party payment API (**Stripe**) for secure online transactions.
- Created dynamic form handling and booking workflows.
- Collaborate with students from other IT principles through the SDLC.
- Communicate with client and showcase deliverables during weekly meetings for updates and feedbacks.
- Worked within an **Agile team environment**, participating in regular stand-ups, reviews, and iterative development to meet client needs.

## 🛠 Tech Stack
- **Language:** PHP v8.2.12
- **Framework:** CakePHP v5.0
- **Database:** MySQL
- **Frontend:** HTML, CSS (Bootstrap 5), JavaScript, jQuery
- **Web Hosting** cPanel
- **APIs & Integrations:**
  - Stripe Payment API
  - Google Maps API
- **Version Control:** Git

## 🚀 Key Features
- Customer-facing booking system with availability checks.
- Admin dashboard for service, branch, and booking management.
- Role-based access for business owner and staff.
- Real-time sync to prevent booking conflicts.
- Secure online payments with Stripe.
- Store location mapping with Google Maps.
- Authentication AND authorisation
- Image uploads/modifications
- Content management (basic CMS)

## 💡 Challenges & Solutions
- **Challenge:** Dynamically updating available time slots based on the business hours set in the admin dashboard.  
  **Solution:** Created a JavaScript-based front-end logic that fetches the updated opening hours and regenerates the available time slots in real time, ensuring customers can only book valid times.
  
- **Challenge:** Preventing double-charging in payment flow.  
  **Solution:** Designed success-page-only payment confirmation logic.

- **Challenge:** Designing an efficient ERD (Entity Relationship Diagram) that supports all features. Midway through the project, the client requested structural changes, and we also identified a more optimal approach for data relationships.  
  **Solution:** Revised the database schema to improve normalisation, scalability, and data integrity while accommodating the new client requirements without disrupting existing development progress.

## 📷 Screenshots 
### Admin Portal
- **Authentication**
  - Log in
  | [Log in page](screenshots/login.jpg)
  - Forgot Password
  | [Forgot Password](screenshots/forgot_pwd.jpg)
  
- **Dashboard Overview**
  | [Admin Dashboard](screenshots/admin_dashboard.jpg)

### Customer Booking Site
- **Make Booking**
  - Select Location
  | [Select Location](screenshots/select_location.jpg)
  - Select Services
  | [Select Services](screenshots/select_services.jpg)
  - Select Time Slot
  | [Select Time Slot](screenshots/select_time.jpg)

- **Checkout**
  | [Checkout](screenshots/checkout.jpg)

## 🔒 Confidentiality Notice
This project was developed for a private client under an NDA.  
All proprietary business logic, data, and source code remain private.  
This README is intended solely to demonstrate my development skills and project experience.
