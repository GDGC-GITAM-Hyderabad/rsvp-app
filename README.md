# RSVP App

A modern event RSVP management application built with Next.js, enabling users to create, manage, and respond to event invitations seamlessly.

## About

RSVP App is a full-stack web application that simplifies event management and attendance tracking. Built with Next.js, it provides a robust platform for:
- Creating and managing events
- Sending and managing invitations
- Tracking attendance and responses
- User authentication and authorization

## Features

- **User Authentication**: Secure login and registration system
- **Event Management**: Create, edit, and delete events
- **RSVP Handling**: Accept or decline event invitations
- **Real-time Updates**: Instant status updates for event changes
- **Responsive Design**: Works seamlessly across all devices

## Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Next.js API Routes
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/rsvp-app.git
   cd rsvp-app
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   Create a `.env` file in the root directory with the following variables:
   ```env
   DB_URL=your_mongodb_connection_string
   TOKEN_SECRET=your_jwt_secret_key
   ```

   Note:
   - For `DB_URL`, use your MongoDB connection string
   - For `TOKEN_SECRET`, use a secure random string for JWT signing

4. **Run Development Server**
   ```bash
   npm run dev
   ```
   The application will be available at `http://localhost:3000`

5. **Build for Production**
   ```bash
   npm run build
   npm start
   ```

## Contributing Guidelines

We welcome contributions to improve the RSVP App! Here's how you can contribute:

### Getting Started

1. Fork the repository
2. Create a new branch for your feature
   ```bash
   git checkout -b feature/your-feature-name
   ```

### Development Process

1. **Code Style**
   - Follow the existing code style and conventions
   - Use meaningful variable and function names
   - Add comments for complex logic

2. **Making Changes**
   - Write clean, maintainable code
   - Include appropriate error handling
   - Add necessary documentation

3. **Testing**
   - Test your changes thoroughly
   - Ensure existing functionality isn't broken
   - Add new tests if necessary

### Submitting Changes

1. Commit your changes with clear, descriptive commit messages
2. Push to your fork
3. Submit a Pull Request with:
   - A clear description of the changes
   - Any relevant issue numbers
   - Screenshots if applicable

### Pull Request Process

1. Update the README.md with details of changes if needed
2. Update any documentation affected by your changes
3. Request review from maintainers
4. Address any feedback from reviewers

## License

MIT License - feel free to use this project for your own purposes.

## Contact

For any queries or support, please open an issue in the GitHub repository.
