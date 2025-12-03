# login

A modern and responsive sign-up form UI designed for user onboarding with clean layout, essential input fields, and easy integration with authentication backend services.

## Tech Stack

- **Frontend**: React + Vite
- **Backend**: FastAPI + SQLAlchemy
- **Design**: Figma ([View Design](https://www.figma.com/design/29HkCjsfiXv6gTPjrXmYwy/Sign-Up-Form--V1---Community-?node-id=0-1&t=PmHlbdkFLCNiw7BE-1))

## Project Structure

```
login/
├── frontend/          # Frontend application
├── backend/           # Backend API
├── README.md          # This file
└── docker-compose.yml # Docker configuration (if applicable)
```

## Getting Started

### Prerequisites

- Node.js 18+ (for frontend)
- Python 3.11+ (for Python backends)
- Docker (optional, for containerized setup)

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
# Follow backend-specific setup instructions in backend/README.md
```

## Features

- Responsive sign-up form UI
- Clean layout and essential input fields
- Easy integration with authentication backend services
- Email and password authentication
- Password reset functionality
- Account information display

## API Endpoints

- `POST /api/register` - Create a new user account
- `POST /api/login` - Log in to an existing user account
- `POST /api/reset-password` - Reset a user's password
- `GET /api/account` - Get the currently logged in user's account information

## License

MIT
