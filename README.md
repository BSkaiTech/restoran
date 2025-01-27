# Restoran - Bootstrap Restaurant Website Template

A modern, responsive restaurant website template built with Bootstrap 5. This template features a clean design, smooth animations, and a fully functional booking system.

## Features

- 🎨 **Modern Design**: Clean and professional Bootstrap 5 based design
- 📱 **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- ⚡ **Fast Loading**: Optimized assets and efficient code structure
- 🎭 **Smooth Animations**: WOW.js integration for scroll animations
- 📅 **Booking System**: Interactive booking form with date/time picker
- 🍽️ **Menu Display**: Beautiful menu showcase with tabs
- 👥 **Team Section**: Display your restaurant team members
- 💬 **Testimonials**: Customer reviews carousel
- 🌐 **Multi-page**: Complete website with multiple pages

## Pages

- **Home** (`index.html`) - Main landing page with hero section, services, about, menu, booking, team, and testimonials
- **About** (`about.html`) - Detailed information about the restaurant
- **Service** (`service.html`) - Services offered by the restaurant
- **Menu** (`menu.html`) - Complete menu with categories
- **Booking** (`booking.html`) - Table reservation form
- **Team** (`team.html`) - Team members showcase
- **Testimonial** (`testimonial.html`) - Customer testimonials
- **Contact** (`contact.html`) - Contact information and form

## Technologies Used

- **Bootstrap 5**: Frontend framework
- **jQuery**: JavaScript library
- **WOW.js**: Scroll animations
- **Owl Carousel**: Testimonials carousel
- **Tempus Dominus**: Date/time picker
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Heebo, Nunito, Pacifico)

## Project Structure

```
restoran/
├── css/
│   ├── bootstrap.min.css
│   └── style.css
├── js/
│   └── main.js
├── img/
│   ├── about-*.png
│   ├── menu-*.png
│   ├── team-*.jpg
│   ├── testimonial-*.jpg
│   └── ...
├── lib/
│   ├── animate/
│   ├── counterup/
│   ├── easing/
│   ├── owlcarousel/
│   ├── tempusdominus/
│   ├── waypoints/
│   └── wow/
├── scss/
│   └── bootstrap/
├── .github/
│   └── workflows/
│       └── static.yml
├── index.html
├── about.html
├── booking.html
├── contact.html
├── menu.html
├── service.html
├── team.html
├── testimonial.html
└── README.md
```

## Getting Started

### Prerequisites

- A modern web browser
- A local web server (optional, for development)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/restoran.git
cd restoran
```

2. Open `index.html` in your web browser, or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

3. Navigate to `http://localhost:8000` in your browser

## Customization

### Colors

The primary color scheme can be customized in `css/style.css`:
```css
:root {
    --primary: #FEA116;
    --light: #F1F8FF;
    --dark: #0F172B;
}
```

### Content

- Update restaurant information in HTML files
- Replace images in the `img/` directory
- Modify menu items in `menu.html` and `index.html`
- Update team member information in `team.html`
- Customize testimonials in `testimonial.html`

### Styling

- Main stylesheet: `css/style.css`
- Bootstrap customization: `scss/bootstrap/`
- Component-specific styles are in `css/style.css`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Deployment

### GitHub Pages

The repository includes a GitHub Actions workflow (`.github/workflows/static.yml`) for automatic deployment to GitHub Pages.

1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select source as "GitHub Actions"
4. The site will be automatically deployed

### Other Hosting Services

You can deploy this static website to any hosting service:
- Netlify
- Vercel
- AWS S3
- Any static hosting service

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## Credits

- **Template Design**: Rokyang Group
- **Bootstrap**: [Bootstrap Team](https://getbootstrap.com/)
- **Icons**: [Font Awesome](https://fontawesome.com/)
- **Fonts**: [Google Fonts](https://fonts.google.com/)

## Changelog

### Version History

- **2025-01-27**: Update documentation and project structure
- **2025-01-10**: Refactor CSS structure and optimize stylesheet loading
- **2024-12-15**: Update dependencies and improve performance
- **2024-11-25**: Fix accessibility issues and improve SEO meta tags
- **2024-10-18**: Enhance booking form validation and user experience
- **2024-09-12**: Update menu items and pricing information
- **2024-08-05**: Improve responsive design and mobile navigation
- **2024-07-10**: Add GitHub Actions workflow for static site deployment
- **2024-06-20**: Update image assets and optimize loading
- **2024-05-15**: Initial commit: Bootstrap restaurant template

## Support

For support, email bsky3419.tech@gmail.com or open an issue in the repository.

## Acknowledgments

- Thanks to all contributors who have helped improve this template
- Special thanks to the Bootstrap team for the amazing framework
- Thanks to the open-source community for the libraries used in this project
