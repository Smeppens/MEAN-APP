# Software Engineering Code Sample

**Author:** Shawn Eppens

## Overview

This code sample is from Travlr Getaways, a full-stack web application I developed as part of my Computer Science coursework and later cleaned up for use in my GitHub portfolio.

The project demonstrates server-side application structure, routing, controllers, templating, static assets, and JSON-based data handling using Node.js and Express.

## Tech Stack

- JavaScript
- Node.js
- Express
- Handlebars (`hbs`)
- Morgan
- Cookie Parser
- HTTP Errors
- HTML/CSS
- JSON

## Run Locally

```bash
git clone https://github.com/Smeppens/MEAN-APP.git
cd MEAN-APP/travlr
npm install
npm start
```

Then open:

`http://localhost:3000`

## Project Structure

```text
travlr/
├── app.js
├── bin/
│   └── www
├── app_server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── views/
├── data/
│   └── trips.json
├── public/
│   ├── css/
│   ├── images/
│   └── *.html
├── package.json
└── package-lock.json
```

## What This Sample Demonstrates

This project demonstrates my experience with:

- Structuring a Node.js and Express application
- Creating and organizing application routes
- Separating routing and controller logic
- Rendering dynamic content with Handlebars templates
- Working with JSON data
- Managing application dependencies with npm
- Organizing frontend and server-side application files

## Notes

This repository originated as a school-era learning project and was later cleaned up for GitHub portfolio use. It is intended to demonstrate application structure, routing, templating, and local development setup rather than production deployment.

## Full Repository

https://github.com/Smeppens/MEAN-APP/
