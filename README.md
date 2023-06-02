# Passport Login Node

Passport Login Node is a simple web application that demonstrates user authentication and registration using Passport.js in a Node.js environment.

## Features

- User registration with password hashing
- User login with authentication
- Session management
- Logout functionality

## Installation

1. Clone the repository:

```
git clone <repository_url>
```

2. Navigate to the project directory:

```
cd passport-login-node
```

3. Install the dependencies:

```
npm install
```

4. Create a `.env` file in the root directory and provide the following configuration:

```
SESSION_SECRET=your_session_secret
```

## Usage

1. Start the application:

```
npm start
```

2. Open your web browser and visit `http://localhost:3000`.

## Dependencies

- [bcrypt](https://www.npmjs.com/package/bcrypt): Password hashing library
- [dotenv](https://www.npmjs.com/package/dotenv): Loads environment variables from a `.env` file
- [ejs](https://www.npmjs.com/package/ejs): Templating engine for rendering views
- [express](https://www.npmjs.com/package/express): Web application framework
- [express-flash](https://www.npmjs.com/package/express-flash): Flash messages middleware for Express
- [express-session](https://www.npmjs.com/package/express-session): Session middleware for Express
- [method-override](https://www.npmjs.com/package/method-override): Middleware for HTTP method override
- [nodemon](https://www.npmjs.com/package/nodemon): Development utility for auto-restarting the server
- [passport](https://www.npmjs.com/package/passport): Authentication middleware for Node.js
- [passport-local](https://www.npmjs.com/package/passport-local): Passport strategy for authenticating with a username and password
