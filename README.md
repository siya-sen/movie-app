# Movie App

A React application to browse popular movies and manage your favorites.  
Built with React, Context API, React Router, and TMDB API.

---

## Features

- Browse popular movies  
- Search movies by name  
- Add/remove favorite movies (stored in localStorage)  
- Responsive UI for desktop and mobile  

---

## Tech Stack

- **Frontend:** React, React Router, Context API  
- **API:** TMDB (The Movie Database)  
- **Styling:** CSS  

---

## Screenshots

![Home Page](screenshots/home.png)  
![Favorites Page](screenshots/favorites.png)  

*(Optional: add screenshots or GIFs of your app here)*

---

## Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/siya-sen/movie-app.git
cd movie-app
2.Install dependencies

 npm install

3.Add your TMDB API key
Replace the API key in src/services/api.js:

const API_KEY = "YOUR_TMDB_API_KEY";

4.Run the development server

npm run dev

5.Open your browser at http://localhost:5173

Notes:
This project uses localStorage to persist favorite movies
The search input automatically handles spaces and special characters
