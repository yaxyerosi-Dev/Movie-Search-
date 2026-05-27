# 🎬 Movie Search App

A simple and modern Movie Search App built using **HTML**, **Tailwind CSS**, and **JavaScript**.  
This app allows users to search for movies using the OMDb API and view detailed movie information inside a modal popup.

---

## 🚀 Features

- 🔍 Search movies by title
- 🎥 Fetch movie data from OMDb API
- 🖼 Display movie posters
- ⭐ Show movie details:
  - Title
  - Year
  - Genre
  - IMDb Rating
  - Actors
  - Plot
- 📱 Fully responsive UI
- 🎨 Modern Tailwind CSS design
- ⌨ Search with Enter key support
- ❌ Modal popup close functionality

---

## 🛠 Technologies Used

- HTML5
- Tailwind CSS
- JavaScript (Vanilla JS)
- OMDb API

---

## 📂 Project Structure

```bash
movie-search-app/
│
├── index.html
├── app.js
└── README.md
```

---

## ⚡ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/movie-search-app.git
```

2. Open the project folder

```bash
cd movie-search-app
```

3. Run the project

Simply open `index.html` in your browser.

---

## 🔑 OMDb API Setup

This project uses the OMDb API.

Replace the API key inside `app.js`:

```javascript
const API_KEY = "YOUR_API_KEY";
```

Get your free API key from:

https://www.omdbapi.com/

---

## 📸 Screenshots

### Home Page

- Search movies
- Responsive movie cards

### Movie Details Modal

- Poster
- Rating
- Genre
- Plot
- Actors

---

## 📜 How It Works

1. User enters a movie name
2. App sends request to OMDb API
3. Movies are displayed as cards
4. Clicking **View Details** opens modal with full movie information

---

## 🧠 Main JavaScript Functions

### `searchMovies()`

Fetches movies from OMDb API.

### `displayMovies(movies)`

Displays movie cards dynamically.

### `getMovieDetails(id)`

Fetches detailed movie information and opens modal.

---

## 📱 Responsive Design

The application is optimized for:

- Mobile devices
- Tablets
- Desktop screens

---

## ✨ Future Improvements

- Add pagination
- Add dark/light mode
- Add favorites/watchlist
- Add loading spinner
- Add movie trailers
- Improve error handling

---

## 👨‍💻 Author

Developed by Yaxye Rosi

---

## 📄 License

This project is open-source and free to use.
