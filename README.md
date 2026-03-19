# Review Web Application

## Overview
This is a application created by The Prabesh!! For sharing the experience of your Dev Journey!!🙏

## Features
- User authentication (login/signup)
- Submit and manage reviews
- View reviews from other users
- Search reviews by product/service name
- Rate and filter reviews
- User profiles and review history

## Project Structure
```
review-app/
├── frontend/          # React frontend application
│   ├── src/
│   ├── public/
│   └── package.json
├── backend/           # Node.js/Express backend
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── package.json
├── database/          # Database configuration
│   └── schema.md
└── README.md
```

## Technologies Used
- **Frontend**: React, HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Package Manager**: npm

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local or cloud instance)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/prabeshbhandari25/Prabesh-Area.git
   cd Prabesh-Area
   ```

2. Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```

3. Install frontend dependencies:
   ```bash
   cd ../frontend
   npm install
   ```

### Running the Application

1. Start the backend server (from `backend/` directory):
   ```bash
   npm start
   ```
   The backend will run on `http://localhost:5000`

2. Start the frontend development server (from `frontend/` directory):
   ```bash
   npm start
   ```
   The frontend will open at `http://localhost:3000`

## API Endpoints
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login user
- `GET /api/reviews` - Get all reviews
- `POST /api/reviews` - Create a new review
- `GET /api/reviews/:id` - Get review by ID
- `PUT /api/reviews/:id` - Update a review
- `DELETE /api/reviews/:id` - Delete a review

## Contributing
If you would like to contribute to the project, feel free to fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.