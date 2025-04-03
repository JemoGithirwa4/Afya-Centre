# Afya Centre - Health & Nutrition Platform

![Afya Centre Logo](Afya%20logo.png)

A comprehensive health and nutrition web application offering personalized diet plans, workout routines, and health resources.

## Features

- **Diet Plans**:
  - Keto diet plan
  - Carnivore diet plan
  - Lactating mother's plan
  - Children's nutrition plan
  - Cardiovascular health plan
  - Muscle gain plan

- **Workout Programs**:
  - HIIT workouts
  - Strength training
  - Home workouts
  - Cardiovascular exercises

- **Health Resources**:
  - Nutrition books (Atomic Habits, Obesity Code, Navy Seal)
  - Educational materials

- **User System**:
  - Account creation
  - Login functionality
  - Personalized recommendations

## Installation

1. Clone the repository:
   ```bash
   git clone [repository-url]
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up MySQL database:
   - Run `Afya Centre db.sql` to create database schema
   - Configure credentials in `database.js`

4. Start the application:
   ```bash
   node app.js
   ```

## File Structure

```
Afya Centre/
├── public/                 # Public assets
│   ├── css/                # Stylesheets
│   ├── html/               # HTML pages
│   ├── images/             # Image assets
│   ├── javascript/         # Client-side scripts
│   └── [PDF resources]     # Health books
├── Image png/              # Additional images
├── Images/                 # More image assets
├── app.js                  # Main application file
├── database.js             # Database configuration
├── package.json            # Project dependencies
└── [HTML pages]            # Various feature pages
```

## Technologies Used

- Frontend:
  - HTML5
  - CSS3
  - JavaScript

- Backend:
  - Node.js
  - Express.js
  - MySQL

- Additional:
  - Various npm packages (see package.json)

## License

ISC License (see package.json for details)
