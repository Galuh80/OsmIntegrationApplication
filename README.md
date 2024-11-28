# OSM Integration Web Application

## Project Structure
- `backend/`: Django REST Backend
- `frontend/`: React Frontend

## Development Setup

### Backend
1. Navigate to backend directory
2. Create virtual environment: `python3 -m venv venv`
3. Activate venv: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Run migrations: `python manage.py migrate`
6. Start server: `python manage.py runserver`

### Frontend
1. Navigate to frontend directory
2. Install dependencies: `npm install`
3. Start development server: `npm start`

## Running with Root Scripts
- Install backend: `npm run install:backend`
- Install frontend: `npm run install:frontend`
- Start backend: `npm run start:backend`
- Start frontend: `npm run start:frontend`