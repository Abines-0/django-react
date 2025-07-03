📝 Notes App

A full-stack note-taking application built with React 19 + Vite on the frontend and Django + Django REST Framework on the backend. The app supports user registration, login, and secure CRUD operations for personal notes using JWT authentication.

🔗 Live Demo

> Coming soon...


✨ Features

🔐 User Authentication – Register, login, logout with JWT-based session management

🗂️ CRUD Notes – Create, read, and delete personal notes

🔄 Protected Routes – Only logged-in users can access their notes

⚡ Fast Frontend – Built using Vite + React 19

🔧 RESTful API – Backend powered by Django REST Framework

🌐 CORS Configured – Frontend and backend work across domains


🛠️ Tech Stack

Frontend

React 19

Axios

jwt-decode


Backend

Django

Django REST Framework

djangorestframework-simplejwt

django-cors-headers


🔐 Authentication

Authentication is handled with JWT:

On login, the backend returns access and refresh tokens

Frontend stores tokens in memory or localStorage

Protected routes check for valid JWT before granting access


🤝 License

MIT License. Feel free to use and contribute!
