# Excellence Academy - Professional Coaching Center Website

A modern, professional website for coaching centers, training institutes, and educational services. Built with HTML5, Tailwind CSS, and vanilla JavaScript.

## 🎨 Features

- **Light/Dark Mode Toggle** - Fully functional theme switcher with localStorage persistence
- **Responsive Design** - Perfect on mobile (360px+), tablet (768px+), and desktop (1280px+)
- **Glassmorphism Effects** - Modern glass effects on navbar, hero, and auth pages
- **Neumorphism Elements** - Subtle neumorphic design for buttons and stat cards
- **Smooth Animations** - Controlled fade and slide animations
- **Professional Layout** - Clean, academic design suitable for educational institutions

## 📁 File Structure

```
coaching-center-website/
│
├── index.html                # Home page
├── courses.html              # Courses listing
├── about.html                # About us page
├── contact.html              # Contact page
├── login.html                # Login page
├── register.html             # Registration page
├── 404.html                  # Error page
│
├── assets/
│   ├── css/
│   │   └── custom.css        # Glass & neumorphism helpers
│   ├── js/
│   │   └── theme.js          # Theme toggle functionality
│   ├── img/
│   │   └── placeholders/      # Image placeholders
│   └── fonts/                # Font files (if needed)
│
└── README.md
```

## 🎨 Design System

### Color Theme (Education Focused)

**Light Mode:**
- Background: `#F8FAFC`
- Primary: `#1E3A8A` (Deep Academic Blue)
- Accent: `#F59E0B` (Warm Gold)
- Text: `#0F172A`

**Dark Mode:**
- Background: `#020617`
- Primary: `#3B82F6`
- Accent: `#FBBF24`
- Text: `#E5E7EB`

### Typography

- **Headings:** Poppins (Google Fonts)
- **Body:** Inter (Google Fonts)

## 🚀 Getting Started

1. **Clone or download** this repository
2. **Open** `index.html` in a web browser
3. **No build process required** - works directly with CDN resources

## 📱 Pages

### Home (`index.html`)
- Hero section with glassmorphism
- Why Choose Us (3 feature cards)
- Courses overview
- Success statistics
- Testimonials
- CTA section

### Courses (`courses.html`)
- Grid-based course cards
- Course details (duration, mode, description)
- Enroll buttons

### About (`about.html`)
- Mission & Vision
- Teaching Methodology
- Instructor highlights
- Core Values

### Contact (`contact.html`)
- Centered contact form
- Contact information cards
- Map placeholder

### Login/Register (`login.html`, `register.html`)
- Centered glass cards
- No navbar (clean auth experience)
- Theme toggle in top-right corner

### 404 (`404.html`)
- Minimal error page
- Back to home button
- Quick navigation links

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Vanilla JavaScript** - Theme toggle functionality
- **Google Fonts** - Poppins & Inter

## ✨ Custom Features

### Glassmorphism
Applied to:
- Navbar
- Hero section
- Login/Register cards

### Neumorphism
Applied to:
- Buttons
- Stat cards

### Animations
- Fade + slide-up on section entry
- Hover transitions (200-300ms)
- No infinite loops or flashy motion

## 📐 Responsive Breakpoints

- **Mobile:** 360×800, 390×844
- **Tablet:** 768×1024, 800×1280
- **Desktop:** 1280px+

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Customization

### Changing Colors
Edit the Tailwind config in each HTML file's `<script>` tag:

```javascript
tailwind.config = {
    darkMode: 'class',
    theme: {
        extend: {
            colors: {
                'academic-blue': '#1E3A8A',  // Change primary color
                'warm-gold': '#F59E0B',      // Change accent color
            }
        }
    }
}
```

### Adding Content
All pages use semantic HTML and Tailwind classes. Simply modify the content within the existing structure.

## 🔧 Theme Toggle

The theme toggle:
- Persists selection in localStorage
- Works across all pages
- Smooth transitions between themes
- Accessible (ARIA labels)

## 📄 License

This is a client-ready template. Customize as needed for your project.

## 👨‍💻 Development

No build process required. Simply:
1. Edit HTML/CSS/JS files
2. Refresh browser to see changes
3. Deploy to any static hosting service

## 🎓 Perfect For

- Coaching institutes
- Training centers
- Educational academies
- Professional development services
- Online learning platforms

---

**Built with ❤️ for educational excellence**

