# Tarang 2026: Responsive College Event Portal

A responsive front-end website for a college festival. Visitors can browse and filter events, check the day-wise schedule, view a gallery, register for events and contact the organisers. It works on mobile, tablet and desktop.

**Live demo:** https://YOUR-USERNAME.github.io/responsive-college-event-portal/

![Desktop home page](docs/screenshots/desktop-home.png)

## Features
- **Homepage:** festival banner, live countdown, featured events and announcements
- **Event listings:** cards with date, time, venue, description and seats left
- **Filters:** by category, by day and by search text
- **Schedule:** day-wise table that stacks into rows on phones
- **Registration form:** JavaScript validation, inline error messages, success message with a registration ID
- **Gallery:** responsive image grid with a click-to-enlarge view
- **Contact page:** details and a validated enquiry form
- **Dynamic updates:** seat counts change after registration, and organisers can post announcements
- **Responsive design:** mobile-first CSS, media queries, hamburger menu

## Tech stack
| Technology | Used for |
|---|---|
| HTML5 | Semantic structure, forms, table, navigation |
| CSS3 | Flexbox, Grid, custom properties, media queries |
| JavaScript (vanilla) | DOM manipulation, event listeners, validation, localStorage |

## Screenshots
| Mobile home | Mobile menu | Mobile schedule |
|---|---|---|
| ![](docs/screenshots/mobile-home.png) | ![](docs/screenshots/mobile-menu.png) | ![](docs/screenshots/mobile-schedule.png) |

## Project structure
```
├── index.html
├── css/style.css
├── js/script.js
├── images/
└── docs/screenshots/
```

## How to run
1. Clone the repository: `git clone https://github.com/YOUR-USERNAME/responsive-college-event-portal.git`
2. Open `index.html` in your browser (or use VS Code Live Server).
3. Press F12, turn on the device toolbar and test different screen sizes.

## What I learned
- Building pages with semantic HTML5
- Mobile-first layouts with Flexbox, Grid and media queries
- Reading and updating the DOM with JavaScript
- Client-side form validation and error handling
- Handling user interactions with event listeners
- Saving data in the browser with localStorage

## Future improvements
- Connect the forms to a backend or a form service
- Add user login and an admin dashboard
- Add a dark-mode toggle

## Author
**Jyothi**, 3rd year B.Tech AI & Machine Learning
GitHub: [@YOUR-USERNAME](https://github.com/YOUR-USERNAME)
