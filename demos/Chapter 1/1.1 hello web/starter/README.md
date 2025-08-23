# Hello Omar Web App

A simple Node.js web application that displays an HTML page with a button. When clicked, the button sends a GET request to the server which prints "hello Omar" to the console.

## Features

- Clean, centered HTML interface
- Express.js backend server
- API endpoint that prints to console
- Real-time response display on the webpage

## Setup Instructions

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Run the application:**
   ```bash
   npm start
   ```
   
   Or for development with auto-restart:
   ```bash
   npm run dev
   ```

3. **Open your browser and go to:**
   ```
   http://localhost:3000
   ```

4. **Click the button** to see "hello Omar" printed in the server console!

## Project Structure

```
complete/
├── package.json          # Project configuration and dependencies
├── app.js               # Express server
├── public/
│   └── index.html       # HTML webpage with button
└── README.md            # This file
```

## How It Works

1. The Express server runs on port 3000
2. The HTML page is served from the `public` directory
3. When the button is clicked, JavaScript sends a GET request to `/api/hello-omar`
4. The server prints "hello Omar" to the console and sends back a JSON response
5. The webpage displays the server's response

## API Endpoint

- **GET** `/api/hello-omar` - Prints "hello Omar" to server console and returns JSON response
