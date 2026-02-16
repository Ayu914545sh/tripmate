# Carpooling Application 

This is a full-stack web application with a **Django** backend and **React** frontend.

## Why this App?
**TripMate** reimagines daily commuting. With rising fuel costs and traffic congestion, single-occupancy vehicles are inefficient. This platform connects drivers with empty seats to commuters going the same way.
- **Sustainable:** Reduces carbon footprint by sharing rides.
- **Affordable:** Drastically lowers travel costs for passengers.
- **Social:** Trust-based community network.

## Tech Stack
### Frontend
- **React (Vite):** Blazing fast implementation for dynamic user interfaces.
- **Tailwind CSS:** Utility-first framework for modern, glassmorphic, and responsive designs.
- **Lucide React:** Modern, lightweight icon library.

### Backend
- **Django REST Framework:** Robust, secure, and scalable API architecture.
- **Simple JWT:** Secure, stateless authentication using JSON Web Tokens.
- **SQLite:** Lightweight database for development flexibility.


## Project Structure
- `backend/`: Django API (User Auth, Rides, Bookings).
- `frontend/`: React + Vite UI (Tailwind CSS).

## Prerequisites
- Python 3.8+
- Node.js & npm

## Quick Start (Windows)
Double-click the `run_app.bat` file in this directory to start both servers automatically!

OR

## Manual Setup & Run

### 1. Backend (Django)
Open a terminal in the `backend/` folder:
```powershell
cd backend
# Create virtual environment (if not exists)
python -m venv venv
# Activate virtual environment
.\venv\Scripts\Activate.ps1
# Install dependencies
pip install -r requirements.txt
# Run migrations
python manage.py migrate
# Start server
python manage.py runserver
```
*Backend runs at: http://127.0.0.1:8000/*

### 2. Frontend (React)
Open a **new** terminal in the `frontend/` folder:
```powershell
cd frontend
# Install dependencies
npm install
# Start dev server
npm run dev
```
*Frontend runs at: http://localhost:5173/*

## Features
- **User Roles:** Driver & Passenger.
- **Ride Sharing:** Drivers post rides; Passengers search and book.
- **Authentication:** Secure JWT login/registration.
- **Dashboard:** Profile management and booking history.
"# tripmate" 
