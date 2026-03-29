# MEAN-APP / Travlr Getaways

An academic full-stack web application originally built for a school project and later cleaned up for portfolio presentation.

This project uses **Node.js**, **Express**, **Handlebars**, and static frontend assets to serve a travel-themed website. It demonstrates server-side routing, view rendering, reusable partials, and data-driven page content.

## Overview

Travlr Getaways is a travel booking-style web app prototype. It includes:

- Express-based server setup
- Handlebars view templates and partials
- Static frontend pages and shared assets
- A travel page rendered from JSON trip data
- MVC-style folder organization in the `app_server` directory

## Tech Stack

- Node.js
- Express
- Handlebars (`hbs`)
- Morgan
- Cookie Parser
- HTTP Errors

## Run Locally

```bash
git clone https://github.com/Smeppens/MEAN-APP.git
cd MEAN-APP/travlr
npm install
npm start


## Project Structure
text
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
