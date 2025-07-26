# property-listing-frontend
Property Listing Frontend UI
This repository contains the frontend UI for the "Mini Property Listing Dashboard," a project developed for a React Developer skill assessment.

This is a single-page application built with React (using CDN links) and styled with Tailwind CSS. It provides a modern, responsive interface for users to interact with property data. The application is fully decoupled from the backend and communicates via a RESTful API to fetch, display, add, and delete property listings.

Live Site URL
The live version of this frontend is hosted on Netlify:
[https://<your-netlify-site-name>.netlify.app](https://property-listing-app.netlify.app/)

Core Technologies
Library: React

Styling: Tailwind CSS

HTTP Client: Native Fetch API

Features
View and filter property listings in real-time.

Search properties by name or location.

Add new properties via a sleek, modern form.

Delete existing properties with a confirmation step.

View property details in an elegant modal window.

Fully responsive design with a dark mode option.

Subtle animations for a smoother user experience.

Local Setup and Installation
To run this frontend on your local machine, please follow these steps:

Prerequisites

Ensure the backend server is running first, as this application depends on its API.

Clone the Repository

git clone <your-repo-url>
cd property-listing-frontend

Run the Application

No build step or local server is required. Simply open the index.html file in your web browser.

Connect to the Backend

Inside the index.html file, make sure the API_BASE_URL constant points to the correct address of your running backend server (e.g., http://localhost:3001 for local development or the live Render URL for production).
