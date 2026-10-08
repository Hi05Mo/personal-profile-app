# Personal Profile App

A simple personal profile server built with Node.js and Express.js.

## Description

This project provides a basic personal profile through different Express.js routes.

It includes routes for the homepage, hobbies, skills, and a JSON API that returns the complete profile information.

## Technologies

* JavaScript
* Node.js
* Express.js
* CommonJS

## Usage

Start the server with:

```bash
npm start
```

The server runs on:

`http://localhost:3000`

Available routes:

```text
GET /
GET /hobbies
GET /skills
GET /api/profile
```

### Profile API

The `/api/profile` endpoint returns the profile information in JSON format:

```json
{
  "name": "Camper Bot",
  "hobbies": ["cycling", "boating", "guitar"],
  "skills": ["JavaScript", "Node.js", "Express.js"]
}
```

## Project Structure

```text
build-a-personal-profile-app/
├── server.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## License

ISC
