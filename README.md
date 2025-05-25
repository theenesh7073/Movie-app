# Movie Search App 🎬

A modern React app to search for movies and view trending movies, powered by [The Movie Database (TMDB) API](https://www.themoviedb.org/) and [Appwrite](https://appwrite.io/) for search analytics.

## Features

- 🔍 **Search** for movies and TV shows in real-time
- 📈 **Trending Movies** section (fetched from TMDB)
- 🗂️ **Appwrite integration** to track and store search analytics
- ⚡ **Debounced search** for better performance
- 🎨 Styled with Tailwind CSS

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/movie-search-app.git
cd movie-search-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up environment variables

Create a `.env` file in the root with the following (replace with your own keys):

```env
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
```

### 4. Start the development server

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) to view the app.

## Folder Structure

```
src/
  components/
    MovieCard.jsx
    search.jsx
    spinner.jsx
  App.jsx
  appwrite.js
  index.css
```

## Technologies Used

- [React](https://react.dev/)
- [Appwrite](https://appwrite.io/)
- [TMDB API](https://www.themoviedb.org/documentation/api)
- [Tailwind CSS](https://tailwindcss.com/)

## Credits

- Movie data from [TMDB](https://www.themoviedb.org/)
- Analytics powered by [Appwrite](https://appwrite.io/)

## License

MIT

---

**Happy movie searching!**
