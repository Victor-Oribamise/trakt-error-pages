# Trakt System Error Pages

Custom error pages for Trakt System platform hosted on Heroku.

## Usage

These pages are served via GitHub Pages and used by Heroku when the application is unavailable.

## Heroku Configuration

```bash
heroku config:set ERROR_PAGE_URL=https://kquika.github.io/trakt-error-pages/index.html
heroku config:set MAINTENANCE_PAGE_URL=https://kquika.github.io/trakt-error-pages/index.html
```

## Pages

- `index.html` - Main error page (503 Service Unavailable)