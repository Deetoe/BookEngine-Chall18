# 21 MERN: Book Search Platform

![License](https://img.shields.io/badge/License-MIT-blue.svg)  
<img alt="React" src="https://img.shields.io/badge/React-18+-blue.svg">
<img alt="GraphQL" src="https://img.shields.io/badge/GraphQL-16+-purple.svg">
<img alt="Apollo" src="https://img.shields.io/badge/Apollo-3.7+-blueviolet.svg">
<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-4.4+-green.svg">
<img alt="Express" src="https://img.shields.io/badge/Express-4.17+-green.svg">
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-16+-green.svg">

## Overview

This web application serves as a Google Books API-powered search engine, originally built using RESTful routes but enhanced by transitioning to a GraphQL API powered by Apollo Server. Constructed with the MERN stack (MongoDB, Express.js, React, Node.js), it enables users to browse for books, register or log in, save their favorite books, and manage their personal book list. The project emphasizes the streamlined data management benefits of GraphQL compared to traditional REST methodologies.

## Table of Contents

- Getting Started  
- How to Use  
- Key Features  
- API Structure  
- Contributions  
- License  
- Contact Info

## Getting Started

```bash
# Clone this repository to your machine
git clone https://github.com/your-username/mern-book-search-engine.git

# Move into the app's directory
cd mern-book-search-engine

# Install all dependencies for both front-end and back-end
npm install

# Build the project
npm run build

# Launch the development environment
npm run dev
How to Use
Once the app is running, you’ll be able to:

Look up books using the Google Books API

Sign up or log in to a personal account

Save books to your profile

View your saved book list

Remove books from your collection

Access the application locally via: http://localhost:3000

Key Features
Secure User Accounts: Sign up and manage your book list

Book Discovery: Browse and find books through live search functionality

Mobile-Friendly UI: Clean, responsive interface for all screen sizes

Database Integration: MongoDB is used to persist user and book data

GraphQL-Driven Backend: Simplifies querying and mutations with a single endpoint

Apollo Client Integration: Optimized frontend state handling and caching

API Structure
The app leverages GraphQL with the following operations:

Queries:
me: Retrieves profile details and saved books for the authenticated user

Mutations:
login: Verifies user credentials and issues a JWT

addUser: Registers a new user and returns a token

saveBook: Adds a book to the user's saved list

removeBook: Deletes a book from the saved list

Contributions
Developed by Daniel Gonzalez

License
This project is licensed under the MIT License.

Contact Info
If you have questions, suggestions, or feedback, feel free to reach out:
📧 Email: dannygonzr20@gmail.com
🐙 GitHub: Deetoe