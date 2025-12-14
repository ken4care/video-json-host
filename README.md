// Movies
fetch("https://YOUR_USERNAME.github.io/video-json-host/movies.json")
  .then(res => res.json())
  .then(data => setMovies(data.movies));

// TV Shows
fetch("https://YOUR_USERNAME.github.io/video-json-host/tv.json")
  .then(res => res.json())
  .then(data => setShows(data.shows));
