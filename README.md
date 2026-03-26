# Mahad Imran Personal Website

This repository contains the source for my personal website and portfolio.

It is a small static site with a landing page, a projects page, and supporting assets like images and my resume. The site is intended to be easy to host and straightforward to maintain.

## Tech Stack

- HTML
- CSS
- Small amount of vanilla JavaScript for reveal effects

## Project Structure

- `index.html` - main landing page
- `apps/index.html` - projects page
- `background.jpg`, `profile.jpg`, `fasttracker-dashboard.png` - site imagery
- `mahad-imran-resume.pdf` - downloadable resume

## Local Preview

Because this is a static site, you can preview it locally with a simple web server.

```bash
cd personal-profile
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000/`.

## Deployment

This project is intended to be deployed as a static site. It can be hosted on platforms like Vercel without a build step.
