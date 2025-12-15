# Video JSON Host (Movies + TV Shows)

This repository hosts JSON files for movies and TV shows to be served via GitHub Pages.

## 📌 Hosted Files

Once GitHub Pages is enabled on this repository (via `main` / `root`), the following URLs will be available:

-- **Movies:** https://ken4care.github.io/video-json-host/movies.json
-- **TV Shows:** https://ken4care.github.io/video-json-host/tv.json

Replace `YOUR_USERNAME` with your GitHub username when fetching from your site.

## Example fetch usage

```js
// Movies
fetch("https://ken4care.github.io/video-json-host/movies.json")
  .then(res => res.json())
  .then(data => setMovies(data.movies));

// TV Shows
fetch("https://ken4care.github.io/video-json-host/tv.json")
  .then(res => res.json())
  .then(data => setShows(data.shows));
```

Enable GitHub Pages in the repository settings and set the publishing source to the `main` branch (root) to serve these files.
