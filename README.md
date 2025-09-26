# BARBARSHOP

## What It Does
BARBARSHOP is a web app I built for booking barbershop appointments. Users can browse services, pick a time, and book easily. Admins manage bookings and services. It’s simple, mobile-friendly, and built with JavaScript, CSS, and HTML—perfect for showing my full-stack web development skills!

**Note**: This is a demo project. Add payment systems (like Stripe) for real-world use.

## Features
- **Book Appointments**: Choose a date, time, and service (like haircut or shave).
- **User Accounts**: Sign up, log in, and save your info.
- **Service List**: See all services with prices.
- **Admin Dashboard**: View and manage all bookings.
- **Mobile-Friendly**: Looks great on phones and computers.
- **Alerts**: Get email confirmations for bookings.

## Tech Used
- **Backend**: Node.js with Express (fast and simple server).
- **Frontend**: HTML, CSS, JavaScript (clean and responsive).
- **Database**: SQLite (easy setup; supports MongoDB).
- **Tools**:
  - Express for APIs.
  - bcrypt for secure passwords.
  - EJS for templates (or swap with React).
  - Bootstrap for styling.

## How to Set Up
### What You Need
- Node.js 18+.
- Git to clone the repo.
- A web browser.

### Steps
1. Clone the repo:
   ```bash
   git clone https://github.com/abd0o0/BARBARSHOP.git
   cd BARBARSHOP
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Add settings (create `.env` file in the root):
   ```
   PORT=3000
   DATABASE_URL=sqlite://barbershop.db
   SECRET_KEY=your_secret_key
   ```
4. Start the app:
   ```bash
   node app.js
   ```
   Open http://localhost:3000 in your browser.

## How to Use
- **Users**: Sign up at `/signup`, check services at `/services`, book at `/book`.
- **Admins**: Log in at `/admin` (default: admin@example.com, password: admin123).
- **Test API** (optional):
   ```bash
   curl http://localhost:3000/api/services
   ```
   Lists all services as JSON.

