# 🎨 Signup-4 - Modern Sign Up Form

A sleek and modern sign-up interface built with HTML, CSS, and responsive design principles. Features a beautiful card layout with social authentication options.

## ✨ Features

- **Modern Design**: Clean and elegant UI with a beautiful color scheme
- **Responsive Layout**: Adapts seamlessly from mobile to desktop screens
- **Social Authentication**: Sign up via Google and Apple
- **Professional Styling**: Custom CSS with smooth transitions
- **Accessible**: Semantic HTML and proper form elements
- **Lightweight**: No heavy dependencies or frameworks

## 🗂️ Project Structure

```
signup-4/
├── index.html        # Main HTML structure
├── style.css         # Styling and responsive design
├── README.md         # Documentation
├── google.svg        # Google logo
└── apple.svg         # Apple logo
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- SVG files for social icons (google.svg, apple.svg)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/signup-4.git
cd signup-4
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server
```

3. Navigate to `http://localhost:8000` in your browser

## 🎨 Design Details

### Color Palette
- **Primary**: `#8864f0` (Purple)
- **Background**: `#6e56b0` (Dark Purple)
- **Card**: `#292334` (Dark Card)
- **Border**: `#686870` (Gray)
- **Text**: `#f9f9f9` (Light White)

### Typography
- **Font Family**: Poppins, Euclid Circular B
- **Loaded from**: Google Fonts

### Responsive Breakpoints
- Mobile: < 485px
- Tablet: 485px - 580px
- Desktop: ≥ 580px

## 📋 Form Fields

- **Email**: Email input field with placeholder
- **Password**: Secure password input field
- **Social Buttons**: Google and Apple authentication options

## 💻 Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling, Flexbox, and media queries
- **Font Awesome**: Icon library (6.5.1)
- **Google Fonts**: Custom typography
- **Material Symbols**: Icon set

## 📱 Browser Compatibility

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Mobile browsers ✅

## 🔧 Customization

### Changing Colors
Edit the CSS variables in [style.css](style.css):

```css
:root {
  --color-primary: #8864f0;      /* Change primary color */
  --color-border: #686870;       /* Change border color */
  --color-muted: #67666e;        /* Change muted text */
  --color-card: #292334;         /* Change card background */
}
```

### Modifying the Hero Image
Replace the background image URL in [style.css](style.css):

```css
.hero {
  background: url("your-image.jpg");
}
```

## 📝 Notes

- Ensure `google.svg` and `apple.svg` are in the same directory as `index.html`
- The form is currently a static UI (no backend integration)
- Consider adding JavaScript for form validation and submission handling

## 🎯 Future Enhancements

- [ ] Form validation with JavaScript
- [ ] Backend integration
- [ ] Dark mode toggle
- [ ] Additional social providers (GitHub, Microsoft, etc.)
- [ ] Animation improvements
- [ ] Accessibility enhancements

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Mohamwd Rashwan**

---

**Made with ❤️ for modern web design**