# F.A.R.M. HEALTH - Healthcare Management Platform

A comprehensive healthcare management system built with HTML, CSS and JavaScript.

## Overview

F.A.R.M. HEALTH provides a modern platform for managing patient records, appointments, prescriptions, and medical staff coordination across three main portals:

- **Patient Portal** - Access medical records, book appointments, manage  and request prescriptions
- **Doctor Portal** - Manage patient lists, view medical records, track appointments
- **Admin Portal** - System administration. management and create users

## Pages & Routes

- `HealthAppDB.html` - Only to initiate the database
- `index.html` - Home page with portal navigation
- `patients.html` - Patient dashboard
- `doctors.html` - Doctor dashboard
- `admins.html` - Admin dashboard

## Example Login Credentials

### Patient Login

> ##### Note: Only these 3 passwords are hardcode to the email respatively. others are random.

- Email: `lvasilik0@java.com` | Password: `password123`
- Email: `mcharke1@cafepress.com` | Password: `password456`
- Email: `anorvill2@msn.com` | Password: `password789`

### Doctor Login

> ##### Note: Only these 3 passwords are hardcode to the email respatively. others are random.

- Email: `vrilton0@discuz.net` | Password: `password123`
- Email: `ebeardsworth1@mac.com` | Password: `password456`
- Email: `emcquillan2@about.me` | Password: `password789`

### Admin Login

> ##### Note: Admin is fine its password and users are same as the ones in provided JSON.

- Username: `sheilah` | Password: `sheilah123`
- Username: `joella` | Password: `joella123`
- Username: `roselin` | Password: `roselin123`

## Database Structure

### Patients.

Patient details and medical information including (Fetched form server):

- Personal details, NHS number, contact info
- Medical conditions, status, appointments
- Physical measurements (height, weight)
- Fetched form json

### Doctor.

Doctor account credentials and specialties (Fetched form server).

### Admin.

Administrator account credentials (Fetched form server).

### Medicine.

Medication inventory with drug names and IDs (Fetched form server).

### Notes.

Medical notes and patient observations (Fetched form server).

### Prescriptions.

Medication prescriptions with:

- Patient associations, medicine details
- Dosage, frequency, duration information
- Prescription status and dates

### Appointment.

Administrator account credentials.

## Features

- Secure role-based authentication
- Real-time patient status monitoring
- Prescription management system
- Appointment scheduling
- Medical record access
- Admin user management
- Responsive design for all devices

## File Structure

```
src/
├── img/ # Images used by the site
├── Json/ # Example JSON files
├── HealthAppDB.html # Database
├── index.html
├── admins.html
├── doctors.html
├── login.html
├── patients.html
├── style.css # Global stylesheet
├── Coursework-1-CaseStudy.pdf
└── Coursework-1-Details.pdf
```

## Getting Started

1. Setup/initiate Database: `HealthAppDB.html`
2. Open `index.html` in browser
3. Should be good to go.

## Contact

📍 123 Healthcare Street, Dubai Healthcare City, UAE
📧 Email: contact@farmhealthcare.com
📞 Phone: +971 06 6767 676
