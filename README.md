# Link-Up

Link-Up is a real-time chat application that allows users to connect and communicate instantly. Built with modern web technologies, it offers a seamless messaging experience with user authentication, real-time messaging, and profile management.

## Features

- **Real-time Messaging**: Instant message delivery using Socket.IO
- **User Authentication**: Secure signup and login functionality
- **Profile Management**: Update user profile and settings
- **Responsive Design**: Works on both desktop and mobile devices

## Tech Stack

### Frontend
- React with Vite
- Tailwind CSS with DaisyUI for styling
- Socket.IO client for real-time communication
- React Router for navigation
- Zustand for state management
- Axios for API requests

### Backend
- Node.js with Express
- MongoDB with Mongoose ODM
- Socket.IO for real-time functionality
- JSON Web Tokens for authentication
- Bcrypt for password hashing
- Cloudinary for image storage

## Installation

1. Clone the repository
   ```
   git clone <repository-url>
   cd link-up
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Set up environment variables
   - Create a `.env` file in the `backend` directory with the following variables:
     ```
     PORT=5000
     MONGODB_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
     CLOUDINARY_API_KEY=your_cloudinary_api_key
     CLOUDINARY_API_SECRET=your_cloudinary_api_secret
     ```

4. Run the development servers
   - For frontend:
     ```
     cd frontend
     npm run dev
     ```
   - For backend:
     ```
     cd backend
     npm run dev
     ```

## Production Build

To create a production build:

```
npm run build
```

To start the production server:

```
npm start
```

## Project Structure

```
link-up/
├── frontend/          # React frontend
│   ├── public/        # Static assets
│   └── src/           # React source code
│       ├── assets/    # Images and resources
│       ├── components/# Reusable UI components
│       ├── pages/     # Main application pages
│       └── store/     # State management
├── backend/           # Node.js backend
│   └── src/
│       ├── controllers/# Request handlers
│       ├── middleware/ # Express middleware
│       ├── models/     # Database models
│       ├── routes/     # API routes
│       └── lib/        # Utility functions
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the ISC License.

## Author

Rishit Singh 