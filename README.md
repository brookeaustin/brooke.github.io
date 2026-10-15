# Brooke's Portfolio

Multi-page portfolio site built with HTML, CSS, JavaScript, and Bootstrap 5.

## Pages
- `index.html` - Home / About
- `skills.html` - Skills
- `experience.html` - Experience & Education
- `projects.html` - Projects (loaded from `data/projects.json`)
- `contact.html` - Contact

## Features
- Responsive Bootstrap navbar, grid, cards, badges, progress bars, list group, modal, alert
- Projects built with `fetch()` from JSON, filterable by category
- Keyword search on projects
- Project detail modal
- Dark/light mode (remembered between pages)
- Time-based greeting on the home page
- Back-to-top link

## Running locally
`fetch()` needs a web server. In VS Code, right-click `index.html` and pick **Open with Live Server**.
Or from this folder run: `python -m http.server` and open http://localhost:8000

## To do before publishing
- Replace `images/avatar.svg` with a real headshot
- Update the email, LinkedIn, and GitHub links in `contact.html`
- Add `images/resume.pdf`
