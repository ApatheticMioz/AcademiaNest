# Academia Nest Website

A static, multi-page marketing site for the fictional "Academia Nest" learning platform. It highlights course offerings, blog posts, team members, and includes basic signup/login/feedback flows styled with Bootstrap and custom CSS.

## Features
- Landing, courses, blog, about, contact, FAQ, privacy, checkout, feedback, signup, and login pages.
- Responsive layouts leveraging Bootstrap 5 and Font Awesome icons via CDN.
- Course and blog grids with imagery for featured content.
- Simple client-side validation for signup/login forms.
- Shared header/footer navigation with social links and repeated CTAs.

## Structure
```
AcademiaNest/ICT/     # duplicate copy of the site assets (mirrors ICT/)
ICT/                  # primary working copy
  Home.html           # landing page
  Courses.html        # featured/all courses grid
  Blog.html           # curated blog links
  Aboutus.html        # team overview
  ContactUs.html      # contact form + Google Maps embed
  Checkout.html       # static cart/checkout summary
  FAQs.html           # FAQ list
  Feedback.html       # feedback form
  PrivPol.html        # privacy policy
  Signup.html         # signup form
  Login.html          # login form
  *.css               # page-specific styling
  Signup.js           # signup validation
  Login.js            # login validation
  map.osm             # OSM extract (not referenced by the pages)
  academia.png, P*.jpg, *.jpg # images used in the pages
```

## Dependencies
- Runtime: modern browser; no build step.
- CDNs: Bootstrap 5.3, Font Awesome 4/5, Google Fonts (Candara fallback).
- Assets: local images under `ICT/` (duplicated under `AcademiaNest/ICT/`).

## Getting Started
1) Open `ICT/Home.html` directly in a browser, or serve the folder locally:
```
cd ICT
python -m http.server 8000
```
Then visit http://localhost:8000/Home.html

## Development
- Edit HTML/CSS/JS files in `ICT/`. The `AcademiaNest/ICT/` folder is a duplicate copy; keep `ICT/` as the source of truth.
- Image paths are relative; keep assets alongside the pages.
- Forms are static and currently alert on success; there is no backend or persistence.

## Usage Examples
- Preview the courses catalog: open `ICT/Courses.html`.
- Try form validation: open `ICT/Signup.html` or `ICT/Login.html` and submit an invalid email to see the client-side check.
- Read blog links: open `ICT/Blog.html` and follow the external links.

## Build / Run Instructions
- No build required. Serve statically (e.g., `python -m http.server`) or open the HTML files directly.
- There are no package installs or environment setup steps.

## License
MIT
