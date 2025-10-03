# manoj-babu-csc-app

A full-featured CSC home delivery app with simple login options: mobile OTP, Gmail, password, and optionally Aadhaar (but prioritize easy login). Include admin & user dashboards, service order, payment gateway, QR, and document upload.

## Features

- **Easy Login Options:**
  - Mobile OTP
  - Gmail/Google Login
  - Password-based Login
  - Aadhaar (Optional)

- **User Dashboard:** Track orders, view services, manage profile
- **Admin Dashboard:** Manage users, services, orders, and payments
- **Service List:** Browse available CSC services
- **Order Form:** Submit service requests
- **Payment Gateway:** Secure online payments
- **QR Code Support:** Quick service access
- **Document Upload:** Upload required documents for services

## Tech Stack

- **Frontend:** React + Vite
- **Routing:** React Router
- **Backend (Planned):** Firebase
- **Payment (Planned):** Payment Gateway Integration

## Getting Started

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build
```

## Project Structure

```
manoj-babu-csc-app/
├── src/
│   ├── pages/
│   │   ├── Login.jsx
│   │   ├── UserDashboard.jsx
│   │   ├── AdminDashboard.jsx
│   │   ├── ServiceList.jsx
│   │   ├── OrderForm.jsx
│   │   └── Payment.jsx
│   ├── components/
│   ├── firebase/
│   ├── payment/
│   ├── App.jsx
│   └── main.jsx
├── public/
├── package.json
└── vite.config.js
```
