# 🎨 Portfolio Next.js - Modern Web Portfolio

## Overview
A modern, interactive Next.js portfolio website with glassmorphism effects, smooth animations, and professional design. Perfect for showcasing education, qualifications, projects, and skills.

## ✨ Features

✅ **Modern Design** - Glassmorphism effects with blur backgrounds
✅ **Fully Responsive** - Mobile-first responsive design
✅ **Dark/Light Mode** - Theme toggle with localStorage persistence
✅ **Interactive Elements** - Smooth animations and hover effects
✅ **SEO Optimized** - Semantic HTML and metadata
✅ **GitHub Pages Ready** - Pre-configured for deployment
✅ **Fast Performance** - Static site generation
✅ **Easy Customization** - Simple JSON-based content management

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/Avirup14/portfolio-nextjs.git
cd portfolio-nextjs
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run Development Server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) to view in browser.

### 4. Build for Production
```bash
npm run build
npm run start
```

## 📁 Project Structure

```
portfolio-nextjs/
├── app/
│   ├── page.tsx             # Main portfolio page
│   ├── layout.tsx           # Root layout
│   └── globals.css          # Global styles
├── components/
│   ├── Navbar.tsx           # Navigation bar
│   ├── ThemeProvider.tsx    # Theme toggle logic
│   └── components.tsx       # Reusable UI components
├── data/
│   ├── education.json       # Education details
│   ├── projects.json        # Projects showcase
│   └── skills.json          # Skills & expertise
├── package.json             # Dependencies
├── next.config.js           # Next.js configuration
├── tailwind.config.js       # Tailwind CSS config
├── tsconfig.json            # TypeScript config
└── README.md                # Documentation
```

## 🎨 Customization

### Update Personal Information
Edit the JSON files in `data/` folder:

#### `data/education.json`
```json
{
  "degree": "Your Degree",
  "field": "Your Field",
  "institution": "Your University",
  "year": 2025,
  "cgpa": "Your CGPA",
  "highlights": ["Achievement 1", "Achievement 2"]
}
```

#### `data/projects.json`
```json
[
  {
    "title": "Project Name",
    "description": "Project description",
    "tech": ["Tech1", "Tech2"],
    "link": "https://github.com/yourprofile/project",
    "featured": true
  }
]
```

#### `data/skills.json`
```json
[
  {
    "category": "Category Name",
    "skills": [
      { "name": "Skill 1", "level": 90 },
      { "name": "Skill 2", "level": 85 }
    ]
  }
]
```

### Customize Colors
Edit `tailwind.config.js` to change color scheme:
```javascript
theme: {
  colors: {
    primary: '#0ea5e9',    // Cyan
    secondary: '#6366f1'   // Indigo
  }
}
```

### Customize Animations
Edit `app/globals.css` to modify animations:
```css
@keyframes slideIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}
```

## 🌐 Deployment

### GitHub Pages Deployment

1. Update `next.config.js` for GitHub Pages
2. Push to GitHub
3. Go to Settings → Pages
4. Select `gh-pages` branch
5. Your site will be live at `https://Avirup14.github.io/portfolio-nextjs`

### Vercel Deployment (Recommended)

1. Push code to GitHub
2. Visit [vercel.com](https://vercel.com)
3. Import your repository
4. Deploy (automatic on push)

## 📚 Tech Stack

- **Framework**: Next.js 14
- **Styling**: Tailwind CSS 3.3
- **Language**: TypeScript/JavaScript
- **Animations**: Framer Motion
- **Deployment**: GitHub Pages / Vercel

## 🎯 Section Details

### Hero Section
- Animated gradient background
- Glassmorphic hero card
- Call-to-action buttons
- Smooth scroll navigation

### Education Section
- Education cards with glassmorphic design
- Expandable details
- Achievement highlights
- Timeline view

### Projects Section
- Project grid layout
- Hover effects
- Tech stack display
- Link buttons (GitHub, Demo)

### Skills Section
- Categorized skills
- Progress bars
- Skill level indicators
- Interactive hover states

### Contact Section
- Contact form
- Social media links
- Email integration ready
- Responsive layout

## 🔧 Configuration

### Environment Variables (Optional)
Create `.env.local`:
```
NEXT_PUBLIC_SITE_URL=https://yourdomain.com
NEXT_PUBLIC_ANALYTICS_ID=your-analytics-id
```

## 📱 Responsive Breakpoints
- Mobile: 320px
- Tablet: 640px
- Desktop: 1024px
- Large Desktop: 1280px

## 🎓 Future Enhancements

- [ ] Blog section with markdown support
- [ ] Email form integration
- [ ] Google Analytics tracking
- [ ] Testimonials section
- [ ] Experience timeline
- [ ] Case studies
- [ ] Newsletter signup
- [ ] Search functionality

## 📞 Contact & Support

- GitHub: [@Avirup14](https://github.com/Avirup14)
- Email: your.email@example.com
- LinkedIn: [Your Profile](https://linkedin.com)

## 📄 License

MIT License - feel free to use this project for your portfolio!

## 🙏 Credits

Built with ❤️ using Next.js, Tailwind CSS, and modern web technologies.

---

**Ready to customize? Edit the files in the `data/` folder and update your information!** 🚀
