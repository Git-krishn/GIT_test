# TailorFit Example App

This repository contains a minimal full-stack demo with a simple React frontend and a Node backend.

## Structure
- `client/` – static HTML page using React and Tailwind from CDNs.
- `server/` – Node HTTP server handling `/submit` requests and saving orders to `orders.json`.

## Running the Demo
1. Start the server:
   ```bash
   cd server
   node server.js
   ```
2. Open `client/index.html` in a browser. (Use Live Server or any static file server.)

Submitting the form will POST the order data to `http://localhost:3001/submit`.
