# GlowFit - Join the Fitness Journey

##  OVERVIEW

**GlowFit** is a modern, responsive sign-up landing page designed for a fitness or wellness platform. It features a clean hero section, a user-friendly registration form with email/password input, and social login integration (Google). The page is built with semantic HTML and includes Google Analytics tracking.

## FEATURES
- Responsive design (mobile & desktop)
- Hero image with prominent branding
- Sign-up form with email & password fields
- "Sign up with Google" button (frontend UI)
- Client-side form submission handler (with `later()` function stub)
- Google Analytics 4 integration (tracking ID: `G-M89WZD35SS`)
- Footer credits with design inspiration links

## FILE STRUCTURE

```

glowfit/
├── index.html          # Main HTML file
├── style.css           # Styles (referenced but not provided)
├── main.js             # JavaScript (referenced but not provided)
└── vault/
└── image.jpg       # Hero background image

```

##  How To Run

1. Clone or download the repository.
2. Ensure `style.css`, `main.js`, and `/vault/image.jpg` exist in the correct relative paths.
3. Open `index.html` in any modern web browser.

>  **Note:** The page requires JavaScript for full functionality (Google sign-in, form submission). A fallback `<noscript>` message is displayed if JS is disabled.

##  Tech Stack

- **HTML5** – Semantic markup
- **CSS3** – External stylesheet for layout/design
- **JavaScript** – Form handling & social login (implementation required in `main.js`)
- **Google Analytics 4** – Visitor tracking
- **SVG** – Google brand icon

##  Dependencies

- No external CSS/JS frameworks required.
- Google Analytics script loads from `https://www.googletagmanager.com`.
- Placeholder `main.js` – expected to define a `later()` function for form submission.

##  License

See the LICENSE.txt in project root. 

##  Credits

- **Design inspiration:** [Glowree on Twitter](https://twitter.com/GlowretheUX/status/1979711426609734089)
- **Code by:** [Obot Obo](https://oboobotenefiok.netlify.app)

##  Future Improvements

- Add backend endpoint for form `action` attribute.
- Implement actual Google OAuth integration.
- Validate email format & password strength.
- Add loading states to submit button.
- Make the design fully responsive on all devices.
