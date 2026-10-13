# Notes from the valley

A plain static blog about making Transect, served by GitHub Pages from this repository.

Live site: https://fellandfjordstudios.github.io/blog/

## Preview

Run `python3 -m http.server 8000` from this directory and open
http://localhost:8000/. There is no build step.

## Add a post

1. Copy an existing HTML file in `posts/`. Update its title, description,
   canonical URL, social metadata, date, and article text.
2. Add its title, date, and a short summary to `index.html`, newest first.
3. Add an item to `feed.xml`, using the absolute published URL for both
   `link` and `guid`. Keep that GUID stable if the post is edited.
4. Check the page on a narrow screen and follow its links in the local preview.

GitHub Pages publishes the repository root from `main`.
