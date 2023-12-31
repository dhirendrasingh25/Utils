

# Template for MERN Stack Development

This template provides a solid foundation for building MERN stack applications, complete with user authentication using bcrypt and JWT.

## Packages

### Client:

- React
- Redux Toolkit
- Chakra UI and Material UI for styling
- Axios for API calls
- LocalForage for local storage
- Framer Motion for animation
- Form handling with React Hook Form
- Routing with React Router DOM
- Linting with ESLint
- Build setup with Vite
### Server:

- Node.js
- Express
- NodeCache
- MongoDB with Mongoose
- Bcrypt for password hashing
- JSON Web Tokens (JWT) for authentication
- Nodemailer for email functionality
- Middleware like CORS, Helmet, and Morgan
- Environment variables with dotenv
- Caching with node-cache
- Image upload with Cloudinary
## How to Start

Clone the repository:

Bash

    git clone https://github.com/dhirendrasingh25/Utils.git
Use code with caution.

Install dependencies:

Bash

    cd mern-template
    npm install

Create a .env file in the root directory and add the following environment variables:

    MONGODB_URI=mongodb://your-mongodb-uri
    JWT_SECRET=your-secret-key
    CLOUDINARY_URL=your-cloudinary-url
    CLOUDINARY_NAME=your-cloudinary-name
    CLOUDINARY_API_KEY=your-cloudinary-api-key
    CLOUDINARY_API_SECRET=your-cloudinary-api-secret
    EMAIL_USER=your-email-username
    EMAIL_PASSWORD=your-email-password
    Start the development servers:

Bash

    npm run dev

This will start both the client and server development servers.

## Pre-Developed Features

Login and signup: Functional user authentication system with password hashing and JWT-based authorization.
Basic React Router is  setedup with basic responsive Login & Signup Page

## Additional Information

Linting: ESLint is configured for both client and server to ensure code quality.
Build tool: Vite is used for a fast and efficient build process.
Styling: Chakra UI and Material UI are included for flexible and customizable styling options.
Image upload: Cloudinary integration for easy image handling.

## Contributing

Feel free to contribute to this template by creating issues or pull requests.

## License

Dhirendra Singh , December 2023