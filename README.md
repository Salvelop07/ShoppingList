# MERN Shopping List

> Shopping list app, built using the MERN stack 🚀, featuring Redux for easy state management 🛍️, and designed with Reactstrap and react-transition-group for a smooth user experience! 🎉

## Quick Start

Add your MONGO_URI to the default.json file. Make sure you set an env var for that and the jwtSecret on deployment

```bash
# Install dependencies for server
npm install

# Install dependencies for client
npm run client-install

# Run the client & server with concurrently
npm run dev

# Run the Express server only
npm run server

# Run the React client only
npm run client

# Server runs on http://localhost:5000 and client on http://localhost:3000
```

## Deployment

There is a Heroku post build script so that you do not have to compile your React frontend manually, it is done on the server. Simply push to Heroku and it will build and load the client index.html page

## App Info

### Author

Salvador

### Version

1.0.0

### License

This project is licensed under the MIT License
