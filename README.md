# 🎓 CodeCortex ERP System

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-brightgreen?logo=github&logoColor=white)](https://aryanjha05.github.io/SIH/)
[![PWA Ready](https://img.shields.io/badge/PWA-Ready-blue?logo=googlechrome&logoColor=white)](https://web.dev/progressive-web-apps/)
[![Responsive Design](https://img.shields.io/badge/Responsive-Design-orange?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **A comprehensive Educational Resource Planning (ERP) system designed for modern educational institutions, providing seamless management across multiple user roles.**

## 🌟 Features

### 👥 **Multi-Role Support**
- **🔧 Administrator**: Complete system management and oversight
- **👨‍🏫 Faculty**: Teaching and student guidance management  
- **🎓 Student**: Academic progress and hostel management
- **👨‍👩‍👧‍👦 Parents**: Monitor child's academic progress and activities
- **🏠 Warden**: Hostel management and student welfare

### 🎨 **Modern UI/UX**
- **Glassmorphism Design**: Beautiful translucent card-based interface
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Single Horizontal Row**: Compact role card layout for better space utilization
- **Interactive Elements**: Hover effects, animations, and smooth transitions
- **Accessibility**: Touch-friendly interactions and screen reader support

### 🚀 **Progressive Web App (PWA)**
- **PWA Ready**: Manifest file configured for app-like experience
- **Responsive Icons**: Optimized logos for different screen sizes
- **Theme Colors**: Consistent branding across platforms

### 📱 **Responsive Design**
- **Mobile First**: Optimized for mobile devices
- **Adaptive Grid**: Dynamic layout adjustment based on screen size
- **Touch Optimized**: Enhanced touch interactions for mobile users
- **Cross-Platform**: Works seamlessly across all devices and browsers

## 🖼️ Screenshots

### Landing Page
![Landing Page](https://via.placeholder.com/800x400/C4A484/FFFFFF?text=CodeCortex+ERP+Landing+Page)

### Role Selection
![Role Selection](https://via.placeholder.com/800x400/fbc6b6/FFFFFF?text=Role+Selection+Cards)

### Dashboard Example
![Dashboard](https://via.placeholder.com/800x400/FAF0E6/5C4033?text=User+Dashboard)

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/AryanJha05/SIH.git
cd SIH
```

### 2. Open in Browser
Simply open `index.html` in your web browser:
```bash
# Using Python (if available)
python -m http.server 8000

# Using Node.js (if available)
npx serve .

# Or just double-click index.html
```

### 3. Access the Application
Navigate to `http://localhost:8000` (if using a server) or directly open the file.

## 📋 Demo Credentials

For testing purposes, use these credentials:

| Role | Username | Password |
|------|----------|----------|
| Administrator | `admin` | `admin123` |
| Faculty | `faculty` | `faculty123` |
| Student | `student` | `student123` |
| Parents | `parents` | `parents123` |
| Warden | `warden` | `warden123` |

## 🏗️ Project Structure

```
SIH/
├── 📄 index.html          # Landing page with role selection
├── 📄 admin.html          # Administrator dashboard
├── 📄 faculty.html        # Faculty dashboard
├── 📄 student.html        # Student dashboard
├── 📄 parents.html        # Parents dashboard
├── 📄 warden.html         # Warden dashboard
├── 🖼️ logo.jpg            # Application logo
├── 📄 manifest.json       # PWA manifest file
├── 📁 .github/            # GitHub configuration
├── 📁 .vscode/            # VS Code settings
└── 📄 README.md           # Project documentation
```

## 🎯 Core Functionalities

### Administrator Dashboard
- **Dashboard Overview**: System statistics and quick access cards
- **User Management Interface**: Role-based dashboard structure
- **Navigation System**: Clean, organized menu layout
- **Responsive Design**: Adapts to all screen sizes

### Faculty Dashboard
- **Teaching Dashboard**: Comprehensive faculty management interface
- **Class Management**: Schedule and course organization
- **Student Tracking**: Performance monitoring interface
- **Responsive Layout**: Mobile-friendly design

### Student Dashboard
- **Academic Interface**: Student-focused dashboard design
- **Information Display**: Clear presentation of academic data
- **Personal Dashboard**: Customized student experience
- **Mobile Optimized**: Touch-friendly interface

### Parents Dashboard
- **Monitoring Interface**: Parent-specific dashboard layout
- **Progress Tracking**: Visual progress indicators
- **Communication Hub**: Centralized information access
- **Family-Friendly Design**: Intuitive navigation

### Warden Dashboard
- **Hostel Management**: Warden-specific management interface
- **Student Welfare**: Comprehensive resident tracking
- **Administrative Tools**: Streamlined management functions
- **Efficient Layout**: Task-oriented design

## 🎨 Design System

### Color Palette
- **Primary**: `#5C4033` (Rich Brown)
- **Secondary**: `#D0816A` (Warm Coral)
- **Background**: `#C4A484` to `#fbc6b6` (Gradient)
- **Text**: Dark and light variants for optimal contrast
- **Success**: Green variants for positive actions
- **Warning**: Orange/Yellow for alerts

### Typography
- **Font Family**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Base Size**: 16px (1rem)
- **Responsive Scaling**: clamp() function for fluid typography
- **Line Height**: 1.6 for optimal readability

### Layout
- **Grid System**: CSS Grid with responsive breakpoints
- **Card Design**: Glassmorphism with backdrop blur
- **Spacing**: Consistent spacing scale using CSS custom properties
- **Border Radius**: Rounded corners for modern appearance

## 📱 Responsive Breakpoints

| Device | Breakpoint | Layout |
|--------|------------|--------|
| Mobile | ≤ 768px | Single column |
| Tablet | 769px - 1023px | Two columns |
| Desktop | ≥ 1024px | Five columns (horizontal row) |
| Large Desktop | ≥ 1441px | Optimized spacing |
| Ultra-wide | ≥ 1920px | Maximum content width |

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern CSS with custom properties and grid
- **JavaScript**: Vanilla JS for interactivity
- **Font Awesome**: Icons and visual elements

### Progressive Web App
- **Web App Manifest**: Configured for app-like experience
- **Responsive Design**: Optimized for all screen sizes
- **Touch Events**: Enhanced mobile interactions
- **Icon Support**: Multiple icon sizes for different devices

### Development Tools
- **Git**: Version control
- **GitHub**: Code hosting and collaboration
- **VS Code**: Development environment
- **Browser DevTools**: Testing and debugging

## 🌐 Browser Support

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | 80+ | ✅ Full |
| Firefox | 75+ | ✅ Full |
| Safari | 13+ | ✅ Full |
| Edge | 80+ | ✅ Full |
| Opera | 67+ | ✅ Full |
| Mobile Browsers | Latest | ✅ Full |

## 🔧 Installation & Deployment

### Local Development
1. Clone the repository
2. Open `index.html` in a web browser
3. No build process required - it's a static site!

### GitHub Pages Deployment
The site is automatically deployed to GitHub Pages:
```
https://aryanjha05.github.io/SIH/
```

### Custom Domain Deployment
1. Upload all files to your web server
2. Ensure `index.html` is the default page
3. Configure HTTPS for PWA features

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Development Guidelines
- Follow existing code style and structure
- Test on multiple devices and browsers
- Ensure accessibility compliance
- Update documentation for new features

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Aryan Jha**
- GitHub: [@AryanJha05](https://github.com/AryanJha05)
- Email: [contact@aryanjha.dev](mailto:contact@aryanjha.dev)

## 🙏 Acknowledgments

- **Font Awesome** for providing excellent icons
- **CSS Grid** for enabling flexible layouts
- **Progressive Web Apps** for modern web capabilities
- **CodeCortex Learning** for the inspiration and requirements

## 📊 Project Stats

- **Total Files**: 8 HTML files + assets
- **Lines of Code**: ~2,700+ lines
- **Responsive Breakpoints**: 6 major breakpoints
- **User Roles**: 5 distinct roles
- **Browser Compatibility**: Modern browsers supported

## 🔮 Future Enhancements

- [ ] **Backend Integration**: Connect to actual database
- [ ] **User Authentication**: Real login system
- [ ] **Data Persistence**: Save user data
- [ ] **Service Worker**: Offline functionality
- [ ] **Dark Mode**: Theme switching
- [ ] **Enhanced Animations**: More interactive elements
- [ ] **Performance Optimization**: Code splitting and lazy loading

## 📞 Support

If you have any questions or need support:

1. **GitHub Issues**: [Create an issue](https://github.com/AryanJha05/SIH/issues)
2. **Documentation**: Check this README and code comments
3. **Email**: Contact the author directly

---

<div align="center">

**⭐ Star this repository if you find it helpful! ⭐**

Made with ❤️ by [Aryan Jha](https://github.com/AryanJha05)

</div>
