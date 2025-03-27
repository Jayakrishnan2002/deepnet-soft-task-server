# DeepNetSoft Restaurant Server

Backend server for the DeepNet Restaurant management system built with Node.js, Express, and MongoDB.

## Features

- RESTful API endpoints for menu management
- MongoDB integration for data persistence
- CORS enabled for frontend integration
- Environment variable configuration
- Error handling and validation

## Prerequisites

- Node.js (v14 or higher)
- MongoDB Atlas account or local MongoDB installation
- npm or yarn package manager

## Installation

1. Clone the repository
bash
git clone <your-repo-url>
cd server


2. Install dependencies
bash
npm install


3. Create a .env file in the root directory
env
MONGODB_URI=your_mongodb_connection_string
PORT=5000


4. Start the server
bash
npm start


## API Endpoints

### Menus
- GET /api/menus - Get all menus
- POST /api/menus - Create a new menu
- PUT /api/menus/:id - Update a menu
- DELETE /api/menus/:id - Delete a menu

### Menu Items
- POST /api/menus/:id/items - Add item to a menu

## Project Structure
