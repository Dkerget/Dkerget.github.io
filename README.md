# CNE Portfolio Website

A simple professional portfolio website for cloud engineering, infrastructure automation, cybersecurity, and AI operations work.

## Overview

This project is a lightweight static website built with standard web technologies. It is designed to be easy to maintain, fast to load, and portable across static hosting platforms.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Static assets

No frontend framework, package manager, build pipeline, or backend service is required.

## Pages

- `index.html` - Home page
- `about.html` - Professional background
- `projects.html` - Project highlights
- `contact.html` - Contact information

## Project Structure

```text
cne-portfolio/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── README.md
└── assets/
    ├── css/
    ├── images/
    └── docs/
```

## Local Development

Because this is a static site, it can be opened directly in a browser or served with any simple static web server.

Example:

```powershell
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

The site is intended for static web hosting. Any deployment platform that supports static HTML, CSS, JavaScript, and assets can host it.

## Maintenance Notes

- Keep content concise and public-facing.
- Avoid committing credentials, internal infrastructure details, private URLs, account names, or operational notes.
- Store sensitive deployment and DNS information outside the repository.

## License

Private portfolio project.
