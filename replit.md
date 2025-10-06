# Fan Page HTML/CSS Lab Project

## Overview
This is a static HTML/CSS educational project for students to create a fan page for their favorite TV character, celebrity, historical figure, or role model. The project focuses on practicing basic HTML elements and CSS styling.

## Project Structure
- `index.html` - Main HTML file with basic skeleton (to be completed by students)
- `style.css` - CSS styling file with some starter styles
- `U1LAB1.md` - Lab instructions and requirements

## Technology Stack
- HTML5
- CSS3
- Python HTTP Server (for serving static files)

## Running Locally
The project uses Python's built-in HTTP server to serve the static files:
```bash
python -m http.server 5000 --bind 0.0.0.0
```

## Lab Requirements
Students should include:
1. HTML skeleton (html, head, body)
2. At least two header elements (h1, h3, etc.)
3. At least one paragraph element
4. At least one image element
5. At least one anchor element linking to another page
6. All elements nested inside the body
7. Sections encapsulated in `div` elements

## Sections to Create
- Intro/Header section with name, quote, and picture
- About Me section describing what the person is known for
- Achievements/Last Seen section with at least 3 nested divs
- Other section with external website links

## Recent Changes
- 2025-10-06: Initial setup in Replit environment
- 2025-10-06: Configured Python HTTP server on port 5000
- 2025-10-06: Added .gitignore for Python artifacts

## User Preferences
None specified yet.

## Project Architecture
Simple static website served via Python's built-in HTTP server. No build process or dependencies required.
