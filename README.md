
# BARBARSHOP

## What It Does
BARBARSHOP is a simple web app I built for booking barbershop appointments. Users can pick services, choose times, and manage bookings. It shows my skills in web development, databases, and user authentication—great for my portfolio!

**Note**: This is a demo project. Add payment systems (like Stripe) for real use.

## Features
- **Book Appointments**: Pick a date, time, and service (e.g., haircut).
- **User Accounts**: Sign up, log in, and manage profiles.
- **Service List**: Browse available services with prices.
- **Admin Panel**: Admins can view bookings and manage services.
- **Mobile-Friendly**: Works on phones and desktops.
- **Notifications**: Get email confirmations for bookings.

## Tech Used
- **Backend**: Python with Flask (simple web framework).
- **Frontend**: HTML, CSS, JavaScript (basic and clean).
- **Database**: SQLite (easy to set up; supports PostgreSQL too).
- **Tools**:
  - Flask for web routes.
  - SQLAlchemy for database.
  - Bootstrap for styling.

## How to Set Up
### What You Need
- Python 3.10 or higher.
- Git to clone the repo.
- A web browser.

### Steps
1. Clone the repo:
   ```bash
   git clone https://github.com/abd0o0/BARBARSHOP.git
   cd BARBARSHOP
   ```
2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```
3. Install packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Add settings (create `.env` file in the root):
   ```
   SECRET_KEY=your_secret_key
   DATABASE_URL=sqlite:///barbershop.db
   ```
5. Start the app:
   ```bash
   python app.py
   ```
   Open http://localhost:5000 in your browser.

## How to Use
- **Users**: Sign up at `/signup`, browse services at `/services`, book at `/book`.
- **Admins**: Log in at `/admin` to manage bookings (default: admin@example.com, password: admin123).
- **CLI Test** (optional):
   ```bash
   python app.py test
   ```
   Checks if the app runs.

