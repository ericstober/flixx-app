# Flixx App

Flixx app is a dynamic web application built with vanilla JavaScript, HTML, and CSS. It leverages The Move Database (TMDD) API to display up-to-date information on movies and TV shows, including details, search functionality, and trending content.

## Features

- **Now Playing Slider**: Showcases movie currently playing in theaters using a responsive Swiper slider.
- **Search Functionality**: Search for movies and TV shows with full pagination support.
- **Details Pages**: View comprehensive details for selected movies and TV shows.
- **Popular Content**:: Browse the top 20 most popular movies and trending TV shows.
- **Responsive Design**: Optimized for various devices and screen sizes.

## Technologies Used

- HTML
- CSS
- JavaScript
- API: [The Movie Database (TMDB) API](https://www.themoviedb.org)
- Libraries:
  - [Swiper](https://swiperjs.com/) for responsive sliders
  - [Font Awesome](https://fontawesome.com/) for icons

## Installation

1. **Clone the repository**:

```bash
git clone https://github.com/ericstober/flixx-app.git
cd flixx-app
```

2. **Obtain a TMDB API Key**:

   - Sign up at [TMBD](https://www.themoviedb.org) and request an API key.

3. **Configure the API Key**:
   - Open the `js/script.js` file.
   - Locate the section where the API key is defined
   - Replace the placeholder with your actual TMDB API key.

_Note: For production use, consider implementing a backend proxy to securly handle API requests and proctect your API key_

4. **Run the Application**:

- Use a simple local HTTP server to serve the files and view the application

## Project Structure

```
flixx-app/
├── css/
│   ├── style.css
│   └── swiper.css
├── images/
├── js/
│   ├── script.js
│   └── swiper.js
├── lib/
├── webfonts/
├── index.html
├── movie-details.html
├── tv-details.html
├── search.html
└── shows.html
```

## License

This project is open-source and available under the MIT License.
