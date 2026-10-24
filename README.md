# Three HTML Website Projects

This folder contains three standalone static HTML/CSS pages.

1. **Personal Portfolio Website** (`abl1.html`) — profile, education, skills, hobbies, projects, achievements, resume link, and contact information.
2. **Online Shopping Website** (`abl2.html`) — promotional banner, three product cards, prices, discounts, ratings, and contact information.
3. **Student Academic Dashboard** (`abl3.html`) — student details, semester marks, attendance bars, exam schedule, and announcements.

## Technologies
- HTML5 for page structure
- CSS3 embedded in each HTML file
- No framework, build step, backend, or database is included in the supplied pages

## Run locally
Open any HTML file in a browser. Alternatively, run this command from the folder:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000/abl1.html`, `/abl2.html`, or `/abl3.html`.

## Supporting files
- `screenshots.pdf` — rendered page captures for all three websites
- `documentation.pdf` — overview, structure, styling, dependencies, and limitations

## Referenced assets not included
The portfolio references `student.png` and `resume.pdf`. The shopping page references `abl2 img-1.jpg.webp`, `abl2 img-2.jpg.webp`, and `abl2 img-3.jpg.webp`. Add these files beside the HTML files or update the paths.

## Scope and limitations
These are front-end demonstration pages. The shopping page's **Shop Now** buttons have no cart or purchase logic. The resume link expects a separate PDF. Student/contact details should be reviewed before public deployment. No authentication, data persistence, server-side processing, or explicit responsive breakpoints are defined in the supplied source.
