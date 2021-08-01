
# react site for upcoming movies

## How to run

``` bash
npm install

npm start
```

## Used Dependencies

    "autoprefixer": "^7.1.6",
    "babel-core": "^6.26.0",
    "babel-loader": "^7.1.2",
    "babel-preset-es2015": "^6.24.1",
    "babel-preset-react": "^6.24.1",
    "css-loader": "^0.28.7",
    "extract-text-webpack-plugin": "^3.0.2",
    "html-webpack-plugin": "^2.30.1",
    "node-sass": "^4.5.3",
    "postcss-loader": "^2.0.8",
    "sass-loader": "^6.0.6",
    "style-loader": "^0.19.0",
    "webpack": "^3.8.1",
    "webpack-dev-server": "^2.9.3",
    "webpack-merge": "^4.1.1"
    "axios": "^0.17.1",
    "babel-polyfill": "^6.26.0",
    "bootstrap-sass": "^3.3.7",
    "history": "^4.7.2",
    "immutable": "^3.8.2",
    "react": "^16.1.1",
    "react-dom": "^16.1.1",
    "react-redux": "^5.0.6",
    "react-router": "^4.2.0",
    "react-router-dom": "^4.2.2",
    "react-router-redux": "^5.0.0-alpha.8",
    "redux": "^3.7.2",
    "redux-saga": "^0.16.0",
    "store2": "^2.6.0"

## Description

Documentation	https://developers.themoviedb.org/3
	
BaseURL	https://api.themoviedb.org/3
API Key (query name "api_key")	7bd61d5db2476d1307ff393ff142924b
	
Image url	https://image.tmdb.org/t/p/w1280{backdrop_path}
Poster url	https://image.tmdb.org/t/p/w342{poster_path}
	
Genre list	/genre/movie/list
Genre movies	/genre/{genre_id}/movies
	
Movies - popular	/movie/popular
Movies - top rated	/movie/top_rated
Movies - upcomming	/movie/upcoming
	
Search	/search/movie?query={query}
	
Movie details	/movie/{movie_id}
	
Details example:	https://api.themoviedb.org/3/movie/374720?api_key=7bd61d5db2476d1307ff393ff142924b
Image example:	https://image.tmdb.org/t/p/w1280/4yjJNAgXBmzxpS6sogj4ftwd270.jpg
	
	
Routes by page	
Home	/
Genre List	/genres/
Genre	/genres/{genre-name}
Most popular	/most-popular
Top rated	/top-rated
Upcomming	/upcomming
Movie	/movie/{movie-id}
Wishlist (bonus)	/wishlist
Search (bonus)	/search?query={search-query}

## 
