# Academia Nest

A static, multi-page marketing website for an online learning platform. Academia Nest showcases course offerings, blog content, team members, and provides user authentication flows—all built with HTML, CSS, JavaScript, and Bootstrap 5.

## Description

Academia Nest is a responsive static website designed for an educational technology platform. The site includes:

- **Home Page** – Landing page with featured courses and call-to-action sections
- **Courses** – Full course catalog with enrollment options
- **Blog** – Curated educational blog links
- **About Us** – Team member profiles and company information
- **Contact** – Contact form with Google Maps integration
- **User Authentication** – Signup and login pages with client-side validation
- **Checkout** – Course enrollment checkout flow
- **FAQ & Support** – Frequently asked questions and feedback forms
- **Privacy Policy** – Terms and privacy information

## Project Structure

```
academia-nest/
├── Home.html           # Landing page (entry point)
├── Courses.html        # Course catalog
├── Blog.html           # Blog links
├── Aboutus.html        # Team overview
├── ContactUs.html      # Contact form
├── Checkout.html       # Checkout page
├── FAQs.html           # FAQ page
├── Feedback.html       # Feedback form
├── PrivPol.html        # Privacy policy
├── Signup.html         # User registration
├── Login.html          # User login
├── *.css               # Page-specific stylesheets
├── Signup.js           # Signup form validation
├── Login.js            # Login form validation
├── academia.png        # Logo
├── *.jpg               # Course and team images
└── map.osm             # OpenStreetMap data
```

## Installation

No build step or package installation required. This is a static HTML/CSS/JS project.

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) Python 3 for local development server

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/ApatheticMioz/AcademiaNest.git
   cd AcademiaNest
   ```

2. Open directly in browser:
   ```bash
   # Simply open Home.html in your browser
   open Home.html        # macOS
   start Home.html       # Windows
   xdg-open Home.html    # Linux
   ```

   Or serve locally with Python:
   ```bash
   python -m http.server 8000
   # Visit http://localhost:8000/Home.html
   ```

## Usage

- **Browse Courses**: Open `Courses.html` to view the full course catalog
- **Try Form Validation**: Visit `Signup.html` or `Login.html` and test client-side validation
- **Read Blog**: Open `Blog.html` for curated educational content links
- **Contact**: Use `ContactUs.html` to view the contact form and embedded map

## Technologies

- **HTML5** – Semantic markup
- **CSS3** – Custom styling with responsive design
- **JavaScript** – Client-side form validation
- **Bootstrap 5.3** – Responsive grid and components (via CDN)
- **Font Awesome 4/5** – Icons (via CDN)
- **Google Fonts** – Typography

## Status

**Archived / Refactored** – This project has been cleaned up and archived for reference.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.
