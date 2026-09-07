# Vishnu Priya R — Portfolio

A personal developer portfolio built with plain HTML5, CSS3 and vanilla JavaScript (ES6+). No frameworks, no build step — open `index.html` in a browser and it runs.

## Structure

```
portfolio/
│
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   ├── profile.jpg
│   ├── resume.pdf
│   └── projects/
└── README.md
```

## Running locally

Open `index.html` directly in a browser, or serve the folder with any static server, e.g.:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Sections

- Hero introduction with profile photo and resume download
- About
- Experience (internship timeline)
- Projects (Student Management System, Online Food Ordering System)
- Skills
- Education
- Certifications
- Achievements
- Contact (mailto-based form)

## Notes

- Project links are marked "Coming Soon" / "Add GitHub link" rather than fabricated, since live URLs and repository links weren't provided. Swap in real links inside `index.html` under `.project-actions` once available.
- The contact form does not send email on its own — it opens the visitor's email client with the message pre-filled via a `mailto:` link. Wire it up to a backend or a form service (e.g. Formspree) if you want it to submit directly.
- Replace `assets/resume.pdf` with an updated resume file (keep the same filename, or update the `href` in `index.html`) whenever it changes.
- Colors, spacing and type scale are defined as CSS custom properties at the top of `css/style.css` for easy adjustment.
