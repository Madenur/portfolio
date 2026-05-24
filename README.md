# 🚀 Advanced Tech Professional Portfolio

A modern, minimalist portfolio website built with **HTML5, CSS3, and Vanilla JavaScript**. Features CV upload capability, dynamic project management, and sold projects showcase.

## ✨ Features

### Core Sections
- **Hero Section** - Eye-catching intro with CTA button
- **About** - Professional narrative with key strengths
- **Featured Projects** - 8+ projects with filtering
- **Experience Timeline** - Career milestones visualization
- **Technical Skills** - Categorized skill showcase
- **CV Upload** - Drag-and-drop CV upload with preview
- **Contact** - Social links and email

### Special Features
✅ **CV Upload System**
- Drag-and-drop support
- PDF and image support
- Local storage (persists across sessions)
- Download functionality
- File info display

✅ **Project Management**
- 9 pre-loaded sample projects
- Filter by category (All, Hackathons, Startups, Professional, Sold)
- Tech stack badges
- GitHub & Demo links
- Business impact metrics
- **Sold Projects** - Special category for commercialized projects

✅ **Design**
- Minimalist aesthetic (white + purple accents)
- Fully responsive (mobile-first)
- Smooth animations & transitions
- Zero dependencies
- Production-ready

## 📂 Project Structure

```
portfolio/
├── index.html          # Single-file portfolio (all HTML, CSS, JS)
└── README.md           # This file
```

## 🎯 Usage

### Option 1: Direct Deploy
Simply download `index.html` and deploy to:
- **GitHub Pages** - Upload to your `gh-pages` branch
- **Vercel** - Drag and drop
- **Netlify** - Drag and drop
- **Any static hosting** - Works anywhere

### Option 2: Local Development
1. Clone the repository
2. Open `index.html` in your browser
3. Start editing!

## ⚙️ Customization

### Update Your Information

**1. Hero Section** - Edit in HTML:
```html
<h1>Your Name Here</h1>
<div class="tagline">Your Title Here</div>
<p class="subtitle">Your narrative...</p>
```

**2. About Section** - Replace bio and strengths

**3. Contact Links** - Update email, GitHub, LinkedIn, Twitter URLs

**4. Projects** - Edit the `projects` array in JavaScript:
```javascript
{
    id: 1,
    name: "Project Name",
    description: "Short description",
    category: "hackathon", // or "startup", "professional", "sold"
    tech: ["Tech1", "Tech2"],
    github: "https://github.com/...",
    demo: "https://...",
    impact: "Business impact"
}
```

**5. Skills** - Edit skill categories in HTML

**6. Timeline** - Update experience timeline items

### Styling

Color scheme variables (edit `:root` in `<style>`):
```css
:root {
    --primary-color: #7c3aed;        /* Purple */
    --primary-light: #a78bfa;
    --dark-text: #1f2937;
    --light-bg: #f9fafb;
    --white: #ffffff;
}
```

## 🎨 Color Reference

- **Primary Purple**: `#7c3aed`
- **Dark Text**: `#1f2937`
- **Light Background**: `#f9fafb`
- **White**: `#ffffff`

## 💾 CV Upload Feature

The CV upload system works entirely client-side:
1. Upload PDF or image
2. Preview is displayed
3. Data stored in browser's `localStorage`
4. Download CV anytime
5. Persists across browser sessions

**Browser Support**: Works on all modern browsers (Chrome, Firefox, Safari, Edge)

## 📱 Responsive Breakpoints

- **Desktop**: Full layout
- **Tablet** (≤768px): Adjusted grid, adjusted timeline
- **Mobile** (≤480px): Single column, hamburger menu

## 🚀 Performance

- **Load Time**: < 2 seconds (no external dependencies)
- **File Size**: ~43KB (single HTML file)
- **Lighthouse Score**: ~95+ (no bloat)

## 🔧 Browser Compatibility

- Chrome/Brave (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers

## 📦 What's Included

✅ Complete portfolio HTML/CSS/JS
✅ 9 sample projects (edit freely)
✅ CV upload system
✅ Project filtering
✅ Smooth animations
✅ Mobile responsive
✅ Contact section
✅ Experience timeline

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling, flexbox, grid, animations
- **JavaScript (Vanilla)** - No frameworks, no build process
- **LocalStorage API** - For CV persistence

## 📝 Sample Projects Included

1. AI-Powered Data Analytics Dashboard
2. Hackathon Winner: Smart City IoT
3. Microservices Architecture Framework
4. SaaS Startup - DataSync Pro (SOLD)
5. Hackathon Winner: ML Model Serving
6. E-Commerce Platform Optimization
7. Sold Project: Real-time Analytics SaaS
8. Hackathon Winner: Climate Data Platform
9. Startup: AI Interview Assistant

## 🎯 Next Steps

1. **Edit Content** - Replace placeholder text with your info
2. **Update Links** - Add your actual GitHub, LinkedIn, Twitter
3. **Customize Colors** - Modify CSS variables if desired
4. **Add More Projects** - Extend the `projects` array
5. **Deploy** - Push to GitHub Pages, Vercel, or Netlify

## 📞 Support

For questions or customization help, refer to the inline code comments in `index.html`.

## 📄 License

Free to use, modify, and deploy. No attribution required.

---

**Built with ❤️ for tech professionals**
