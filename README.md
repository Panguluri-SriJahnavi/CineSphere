# CineSphere

**Your movies. Your world.**

CineSphere is a movie discovery website that helps people find something worth watching without searching across many platforms. You pick an industry, a mood, a genre and a language, and it recommends real films that match.

**Live site:** https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/

## The problem

Movies, shows and music are spread across many platforms, and the growing number of choices makes it hard to find relevant content quickly.

## What it does

- Covers Hollywood, Bollywood, Tollywood, Kollywood, Mollywood, Sandalwood, Korean cinema, Japanese cinema and world cinema
- Recommends real films, each with its director, year, language and a short plot
- Filters by film industry, mood, genre and language
- Shows a match percentage when you choose moods, and marks the best matches
- Search by movie title or director
- "Surprise me" picks a random film from your current filters
- "Find more like this" starts a new search from a film's moods
- Save films to a watchlist, which stays in your browser
- "Because you saved these" suggests more films based on your watchlist
- Works on phones, tablets and desktops, in light and dark mode

## Who it is for

Tech-savvy urban students aged 18 to 35 who regularly consume digital entertainment.

## Built with

HTML, CSS and JavaScript. It is a single page with no backend, so it runs directly on GitHub Pages.

## Run it locally

1. Download or clone this repository.
2. Open `index.html` in any browser.

## Project structure

```
index.html   The complete website (page, styles, film data and logic)
README.md    This file
```

## Adding more movies

The film list is inside `index.html`. Each film is one line in this format:

```
Title|Year|Industry|Language|Director|genre1,genre2|mood1,mood2|Short plot
```

Add a line, save the file and refresh the page.

## Future scope

- Ratings and where-to-watch information
- Music and TV show recommendations
- User accounts so watchlists sync across devices
