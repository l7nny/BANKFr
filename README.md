# BANKFr - Banking Admin Dashboard

A modern, responsive admin dashboard built with Bootstrap for banking and financial management applications.

## 📋 Overview

BANKFr is a professional admin dashboard template designed for banking systems. It includes authentication pages (login, registration, forgot password) and a clean, intuitive interface for managing financial data and user accounts.

## ✨ Features

- **Responsive Design**: Mobile-first Bootstrap framework
- **Authentication Pages**: Login, registration, and password recovery
- **Modern UI/UX**: Clean and professional interface
- **Dashboard Layout**: Organized grid system for data visualization
- **Cross-browser Compatible**: Works on all modern browsers
- **Fast & Lightweight**: Optimized CSS, SCSS, JavaScript, and HTML

## 🛠️ Technology Stack

- **HTML5** - Semantic markup
- **CSS3 & SCSS** - Styling and preprocessing
- **Bootstrap** - Responsive framework
- **JavaScript** - Interactive functionality
- **jQuery** - DOM manipulation and utilities
- **Font Awesome** - Icon library

## 📊 Project Structure

```
BANKFr/
├── README.md                 # This file
├── index.html               # Main dashboard page
├── login.html               # Login page
├── register.html            # Registration page
├── forgot-password.html      # Password recovery page
├── css/                     # Stylesheet directory
├── js/                      # JavaScript directory
├── vendor/                  # Third-party libraries
└── img/                     # Image assets
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v11.6.0 or higher)
- npm (comes with Node.js)
- Gulp CLI (v2.0.1)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/l7nny/BANKFr.git
   cd BANKFr
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm start
   ```

The dashboard will open in your default browser and automatically reload on file changes.

## 📦 Available npm Scripts

- **`npm start`** - Runs the development server with live reload
- **`npm run build`** - Builds the production-ready files
- **`gulp`** - Default task that builds everything
- **`gulp watch`** - Watches for file changes and live reloads
- **`gulp css`** - Compiles SCSS to CSS and minifies
- **`gulp js`** - Minifies JavaScript files
- **`gulp vendor`** - Copies vendor dependencies to the vendor directory

## 🎨 Customization

### Modifying Styles

Edit SCSS files in the `scss/` directory. Styles are automatically compiled to CSS when using the watch task.

### Adding New Pages

1. Create a new HTML file in the root directory
2. Include the necessary CSS and JavaScript files
3. Follow the existing template structure for consistency

### Updating Dependencies

To update npm packages:
```bash
npm update
```

## 📄 Pages Included

- **Dashboard** - Main admin interface
- **Login** - User authentication page
- **Registration** - New user signup
- **Forgot Password** - Password recovery flow

## 🔒 Security Notes

- This is a template for the frontend only
- Implement proper backend authentication
- Never commit sensitive data or API keys
- Use HTTPS in production
- Validate all user inputs on the server

## 🐛 Troubleshooting

### Gulp not running after `npm install`

Make sure you have the Gulp CLI installed globally:
```bash
npm install -g gulp-cli
```

### Port already in use

The development server uses port 3000 by default. If it's already in use, modify the Gulp configuration or specify a different port.

### Styles not compiling

Clear the cache and reinstall dependencies:
```bash
rm -rf node_modules
npm install
```

## 📝 License

Copyright 2013-2021 Start Bootstrap LLC. Code released under the [MIT License](https://github.com/l7nny/BANKFr/blob/main/LICENSE).

This project is based on [SB Admin 2](https://startbootstrap.com/theme/sb-admin-2/) by Start Bootstrap.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

## 👤 Author

**l7nny** - [GitHub Profile](https://github.com/l7nny)

## 🙏 Acknowledgments

- [Start Bootstrap](https://startbootstrap.com/) - Original theme
- [Bootstrap](https://getbootstrap.com/) - CSS framework
- [Font Awesome](https://fontawesome.com/) - Icon library
- [jQuery](https://jquery.com/) - JavaScript library

## 📞 Support

For issues, questions, or suggestions, please [open an issue](https://github.com/l7nny/BANKFr/issues) on GitHub.

---

**Last Updated:** 2026-05-14
