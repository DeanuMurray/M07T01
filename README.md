# Static Website Deployment - M07T01

## Overview
This module contains a static personal CV website prepared for GitHub Pages deployment.

## Project Files
- index.html - Main CV web page
- my_cv.txt - Deployment information for the CV page
- static_url.txt - Submitted static site URL
- my_cv.jpg - Screenshot evidence

## Local Run
```bash
cd M07T01
python -m http.server 8000
```

Open http://localhost:8000

## Live Deployment
Expected GitHub Pages URL:

https://deanumurray.github.io/M07T01/

If this URL shows 404, enable Pages in the repository settings:
1. Settings
2. Pages
3. Source: Deploy from a branch
4. Branch: main and / (root)
