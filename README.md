# Community Care NGO Website

A modern, responsive website for a non-governmental organization (NGO) built with HTML, CSS, JavaScript, and Bootstrap 5.

## 🌟 Features

### 📱 Fully Responsive Design
- Mobile-first approach
- Optimized for all screen sizes (desktop, tablet, mobile)
- Touch-friendly interface

### 🏠 Home Page
- Hero section with compelling call-to-action
- Animated elements and smooth transitions
- Professional gradient background
- Clear navigation to other sections

### 📋 Volunteer Form
- Comprehensive volunteer application form
- Form validation with real-time feedback
- Multiple areas of interest selection
- Age and availability options
- Success/error message handling

### ℹ️ About Us Section
- Mission and vision statements
- Impact statistics with animated counters
- Professional card-based layout
- Hover effects and animations

### 📞 Contact Information
- Multiple contact methods
- Social media links
- Professional footer design

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling and animations
- **JavaScript (ES6+)** - Interactive functionality
- **Bootstrap 5** - Responsive framework
- **Font Awesome** - Icons
- **Google Fonts** - Typography

## 📁 Project Structure

```
NGO/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software installation required

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. The website will load with all features functional

### Local Development
For development purposes, you can use any local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy color customization. Edit the `:root` section in `styles.css`:

```css
:root {
    --primary-color: #0d6efd;
    --secondary-color: #6c757d;
    /* ... other colors */
}
```

### Content
- Update text content in `index.html`
- Modify form fields in the volunteer section
- Change contact information
- Update impact statistics

### Styling
- Modify `styles.css` for visual changes
- Add new animations or effects
- Customize responsive breakpoints

## 📱 Responsive Breakpoints

- **Mobile**: < 576px
- **Tablet**: 576px - 768px
- **Desktop**: > 768px

## 🔧 Features in Detail

### Form Validation
- Real-time validation feedback
- Required field checking
- Email format validation
- Success/error message display

### Animations
- Scroll-triggered animations
- Counter animations for statistics
- Hover effects on cards and buttons
- Smooth page transitions

### Accessibility
- Semantic HTML structure
- ARIA labels and roles
- Keyboard navigation support
- Screen reader friendly
- Reduced motion support

### Performance
- Optimized images and assets
- Efficient CSS and JavaScript
- Minimal external dependencies
- Fast loading times

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## 📝 Form Data Handling

The volunteer form currently simulates submission. To integrate with a backend:

1. Replace the setTimeout in `script.js` with actual API calls
2. Add proper error handling
3. Implement CSRF protection
4. Add server-side validation

Example API integration:
```javascript
// Replace the setTimeout with actual API call
fetch('/api/volunteer', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
    },
    body: JSON.stringify(formData)
})
.then(response => response.json())
.then(data => {
    showMessage('Thank you for your application!', 'success');
})
.catch(error => {
    showMessage('An error occurred. Please try again.', 'error');
});
```

## 🤝 Contributing

1. Fork the project
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

For questions or support, please contact:
- Email: info@communitycare.org
- Phone: +1 (555) 123-4567

## 🎯 Future Enhancements

- [ ] Multi-language support
- [ ] Blog/news section
- [ ] Donation integration
- [ ] Event calendar
- [ ] Photo gallery
- [ ] Newsletter signup
- [ ] Admin dashboard
- [ ] Database integration

---

**Built with ❤️ for community service organizations** 