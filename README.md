# Couples App Backend

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

## Overview

This repository contains the backend API for a couples relationship application. It provides the server-side logic for user authentication, game management, and data persistence, enabling interactive and engaging experiences for couples.

## Features

* **User Authentication:** Secure registration, login, and logout functionality using JWT.
* **User Profiles:** Management of user account details.
* **Interactive Games:** API endpoints for creating, joining, and playing various games designed for couples.
* **Question Management:** Functionality to handle and serve questions for games.
* **Answer Submission:** Endpoints for users to submit answers within games.
* **Prediction Handling:**  API for making and managing predictions.
* **Score Tracking:** Logic for calculating and storing scores for games.
* **Password Management:** Secure password hashing and the ability to change passwords.
* **Rate Limiting:** Protection against brute-force login attempts.

## Technologies Used

* [Node.js](https://nodejs.org/) - JavaScript runtime environment
* [Express](https://expressjs.com/) - Web application framework for Node.js
* [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) - For JSON Web Token generation and verification
* [bcrypt](https://www.npmjs.com/package/bcrypt) - For password hashing
* [pg](https://www.npmjs.com/package/pg) - PostgreSQL client for Node.js (or your chosen database library)
* [dotenv](https://www.npmjs.com/package/dotenv) - To load environment variables from `.env` files
* [uuid](https://www.npmjs.com/package/uuid) - For generating unique IDs
* [express-validator](https://www.npmjs.com/package/express-validator) - For request body validation
