# Mary Hardy - Portfolio Website

A modern, elegant, and fully responsive portfolio website showcasing my skills, experience, and projects as a Full-Stack Web Developer.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Yes-brightgreen)

## 🌟 Features

- **Modern Design**: Clean, professional UI with contemporary aesthetics
- **Smooth Animations**: Engaging fade-in effects and hover interactions
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Gradient Backgrounds**: Dynamic animated gradient header
- **Interactive Elements**: Smooth transitions and hover effects throughout
- **Accessibility**: Semantic HTML and ARIA labels for better accessibility
- **Fast Loading**: Optimized performance with minimal dependencies
- **SEO Friendly**: Proper meta tags and semantic structure

## 🎨 Design Highlights

- **Color Scheme**: Modern purple gradient with warm accent colors
- **Typography**: Inter (body) and Playfair Display (headings) for elegant contrast
- **Animations**:
  - Floating profile image
  - Gradient shifting background
  - Fade-in-up effects for content sections
  - Smooth hover transitions on cards and buttons
- **UI Components**:
  - Rounded buttons with gradient backgrounds
  - Card-based skill and experience sections
  - Elegant section dividers
  - Glassmorphic form inputs

## 📁 Project Structure

```
portfolio-website/
├── index.html              # Main HTML file
├── styles/
│   └── portfolio.css       # Main stylesheet
├── images/
│   ├── hardy.png           # Profile picture
│   ├── icons/
│   │   ├── js.png          # JavaScript icon
│   │   ├── react.png       # React icon
│   │   ├── nodejs.png      # Node.js icon
│   │   ├── mongo.png       # MongoDB icon
│   │   ├── facebook.png    # Facebook icon
│   │   ├── insta.png       # Instagram icon
│   │   └── twitter.png     # Twitter icon
├── files/
│   └── Mary_Hardy_CV.pdf   # Downloadable CV
└── README.md               # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.) for modifications

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/portfolio-website.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd portfolio-website
   ```

3. **Open in browser**

   - Simply open `index.html` in your preferred web browser
   - Or use a local server (recommended):

     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node.js (http-server)
     npx http-server

     # Using VS Code Live Server extension
     Right-click on index.html → Open with Live Server
     ```

4. **Visit**
   ```
   http://localhost:8000
   ```

## 🎯 Sections

### 1. **Hero/Banner**

- Eye-catching gradient background with animated pattern
- Professional introduction
- Call-to-action buttons (Download CV, Contact)
- Floating profile image with animation

### 2. **About Me**

- Personal information cards
- Clean, organized layout
- Hover effects on info cards

### 3. **Skills**

- Technology stack showcase
- Icon-based skill cards
- Interactive hover animations
- Detailed descriptions of each skill

### 4. **Resume**

- Education timeline
- Professional experience
- Structured grid layout
- Download CV button

### 5. **Footer/Contact**

- Contact form
- Social media links
- Professional dark theme
- Responsive layout

## 🛠️ Customization

### Changing Colors

Edit the CSS variables in `styles/portfolio.css`:

```css
:root {
  --primary-color: #6366f1; /* Main brand color */
  --accent-color: #f59e0b; /* Accent/highlight color */
  --text-primary: #0f172a; /* Main text color */
  --text-secondary: #64748b; /* Secondary text color */
  --gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Updating Content

1. **Personal Information**: Edit the text content in `index.html`
2. **Profile Image**: Replace `images/hardy.png` with your photo
3. **Skills**: Update the skills section with your technologies
4. **Experience**: Modify the resume section with your background
5. **CV**: Replace `files/Mary_Hardy_CV.pdf` with your resume

### Adding Sections

Add new sections following the existing structure:

```html
<section class="your-section" id="your-section">
  <h3 class="section-title text-center">Your Title</h3>
  <p class="section-description text-center">Your description here</p>
  <!-- Your content -->
</section>
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1024px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 📈 Performance Optimization

- Minimal external dependencies
- Optimized images
- Efficient CSS animations
- Lazy loading considerations
- Clean, semantic HTML

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Grid and Flexbox
- **Google Fonts**: Inter & Playfair Display
- **Font Awesome**: Icon library
- **CSS Variables**: For easy theming
- **CSS Animations**: Smooth transitions and effects

## 📝 TODO / Future Enhancements

- [ ] Add dark/light mode toggle
- [ ] Implement project gallery section
- [ ] Add blog section
- [ ] Include testimonials
- [ ] Integrate contact form backend
- [ ] Add loading animations
- [ ] Implement scroll reveal animations
- [ ] Add language switcher
- [ ] Include metrics/statistics section
- [ ] Add downloadable project case studies

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/portfolio-website/issues).

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Mary Hardy**

- Email: abc@def.com
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)
- Portfolio: [yourportfolio.com](https://yourportfolio.com)

## 🙏 Acknowledgments

- Design inspiration from modern portfolio trends
- Icons from Font Awesome
- Fonts from Google Fonts
- Color palette inspired by modern UI design systems

## 📸 Screenshots

### Desktop View

![Desktop Screenshot](screenshots/desktop.png)

### Mobile View

![Mobile Screenshot](screenshots/mobile.png)

---

**Note**: Replace placeholder content (email, GitHub links, screenshots) with your actual information before deploying.

Made with ❤️ by Mary Hardy
