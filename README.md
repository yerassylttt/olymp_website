# Олимпиады по Биологии в Казахстане / Қазақстандағы Биология Олимпиадалары

Welcome to the official website for Biology Olympiads in Kazakhstan! This repository contains the source code for the bilingual (Russian/Kazakh) website providing information about biology competitions for students.

## 🌐 Languages

This website is available in two languages:
- **Russian (Русский)** - Primary language
- **Kazakh (Қазақша)** - Secondary language

## 📁 Project Structure

```
olymp_website/
├── assets/                    # Static assets
│   ├── css/                   # Stylesheets
│   │   ├── normalize.css     # CSS reset
│   │   ├── skeleton.css      # Grid framework
│   │   └── custom.css        # Custom styles
│   ├── images/               # Images and icons
│   │   ├── lang.svg          # Language switcher icon
│   │   └── favicon.png       # Site favicon
│   └── js/                   # JavaScript files
├── pages/                    # HTML pages
│   ├── ru/                   # Russian pages
│   │   ├── olympiads/        # Olympiad detail pages
│   │   │   ├── respa.html
│   │   │   ├── presidential.html
│   │   │   ├── rural.html
│   │   │   └── junior.html
│   │   ├── selection.html    # IBO selection information
│   │   ├── news.html         # News and updates
│   │   ├── syllabus.html     # Syllabus and materials
│   │   ├── tips.html         # Study tips
│   │   └── authors.html      # About the authors
│   └── kz/                   # Kazakh pages (mirror structure)
│       ├── olympiads/
│       └── ...
├── index.html                # Homepage (Russian)
├── .gitignore               # Git ignore rules
└── README.md                # This file
```

## 🏆 Olympiads Covered

The website provides information about the following biology olympiads in Kazakhstan:

1. **Республиканская олимпиада** (Republican Olympiad) - Main four-stage competition for grades 9-11(12)
2. **Республиканская Юниорская олимпиада** (Republican Junior Olympiad) - Competition for grades 7-8
3. **Президентская олимпиада** (Presidential Olympiad) - For grade 11(12) students without prior olympiad experience
4. **Республиканская олимпиада для учеников сельских школ** (Rural Schools Olympiad) - Three-stage competition for students from rural schools

## 🚀 Getting Started

### Prerequisites

No build tools or dependencies are required. This is a static HTML/CSS website.

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yerassylttt/olymp_website.git
   cd olymp_website
   ```

2. Open the website:
   - Simply open `index.html` in your web browser
   - Or use a local web server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js http-server
     npx http-server
     ```

3. Navigate to `http://localhost:8000` in your browser

### File Structure Guidelines

- All Russian pages should be in the `pages/ru/` directory
- All Kazakh pages should be in the `pages/kz/` directory
- CSS files should be in the `assets/css/` directory
- Images should be in the `assets/images/` directory
- Maintain consistent navigation across all pages

## 🎨 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling and responsive design
- **Skeleton CSS** - Lightweight responsive grid framework
- **Normalize.css** - CSS reset for cross-browser consistency
- **IBM Plex Sans** - Google Fonts typography

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Mobile devices (320px - 600px)
- Tablets (601px - 768px)
- Desktop (769px+)

## ♿ Accessibility

The website follows accessibility best practices:
- Semantic HTML5 elements
- ARIA labels and attributes
- Keyboard navigation support
- Screen reader compatibility
- Proper heading hierarchy

## 🔗 Navigation Structure

The main navigation includes:
- **Главная / Басты бет** - Homepage
- **Олимпиады / Олимпиадалар** - Olympiad information (dropdown)
  - Republican Olympiad
  - Presidential Olympiad
  - Rural Schools Olympiad
  - Junior Olympiad
- **Отбор на IBO / IBO-ға іріктеу** - IBO selection process
- **Новости / Жаңалықтар** - News and updates
- **Силлабус** - Study materials and syllabus
- **Советы / Кеңестер** - Study tips
- **Об авторах / Авторлар туралы** - About the authors

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

### Development Guidelines

1. Maintain bilingual content (Russian and Kazakh)
2. Ensure responsive design works on all devices
3. Test accessibility features
4. Keep the codebase simple and maintainable
5. Follow the existing file structure

## 📧 Contact

For questions about the olympiads or website, please refer to the "About Authors" page on the website.

## 📄 License

This project is maintained by the Biology Olympiad Committee of Kazakhstan.

## 🔄 Recent Updates

- Project restructuring and reorganization
- Improved accessibility features
- Enhanced responsive design
- Better SEO optimization
- Consistent styling across all pages

---

**Добро пожаловать!** | **Қош келдіңіздер!**
