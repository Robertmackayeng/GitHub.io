# Robert Mackay - Personal Portfolio

Welcome to my personal website built with **Astro** and **Tailwind CSS**! This is a fast, modern portfolio showcasing projects and skills.

## 🚀 Quick Start

### Prerequisites
- Node.js 16.12 or higher
- npm or yarn

### Installation & Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

The site will be available at `http://localhost:3000`

## 📁 Project Structure

```
src/
├── components/        # Reusable Astro components
│   ├── Navigation.astro
│   ├── HeroSection.astro
│   ├── AboutSection.astro
│   ├── ProjectsSection.astro
│   ├── ContactSection.astro
│   ├── ProjectCard.astro
│   ├── NavLink.astro
│   ├── CTAButton.astro
│   └── Footer.astro
├── layouts/          # Layout templates
│   └── Layout.astro
├── pages/            # Page routes (file-based routing)
│   └── index.astro
└── styles/           # Global CSS styles
    └── global.css

public/               # Static assets
package.json          # Project dependencies
astro.config.mjs      # Astro configuration
tailwind.config.mjs   # Tailwind CSS configuration
```

## 🎨 Technology Stack

- **Framework**: Astro 4.0
- **Styling**: Tailwind CSS 3
- **Language**: Astro (with JSX/TSX support)
- **Deployment**: GitHub Pages

## ✏️ Customization

### Update Your Information

1. **Edit `src/components/HeroSection.astro`** - Update your name and title
2. **Edit `src/components/AboutSection.astro`** - Update about text and skills
3. **Edit `src/components/ProjectsSection.astro`** - Add your projects
4. **Edit `src/components/ContactSection.astro`** - Update contact links and email

### Customize Colors

Edit `tailwind.config.mjs`:
```javascript
theme: {
  extend: {
    colors: {
      primary: '#0066cc',      // Change primary blue
      secondary: '#ff6600',    // Change secondary orange
    },
  },
}
```

### Add More Components

Create new `.astro` files in `src/components/` and import them in your pages.

## 🚀 Deployment

### Deploy to GitHub Pages

1. Push your changes to the `main` branch
2. GitHub Pages will automatically build and deploy (uses Astro's built-in GitHub Pages support)
3. Your site will be live at `https://robertmackayeng.github.io`

## 📦 Build Output

When you run `npm run build`, Astro generates:
- Static HTML files
- Optimized CSS and JavaScript
- Ready for deployment to GitHub Pages

## 🔗 Key Features

- ⚡ **Ultra-fast performance** - Astro ships minimal JavaScript
- 🎯 **File-based routing** - Pages automatically created from `src/pages/`
- 🎨 **Tailwind CSS** - Utility-first styling framework
- 📱 **Responsive design** - Mobile-first approach
- 🔍 **SEO friendly** - Optimized for search engines
- 🎭 **Component-based** - Reusable `.astro` components

## 📝 Next Steps

1. ✅ Astro project initialized
2. ✅ Tailwind CSS configured
3. ✅ Components created
4. **TODO**: Update your personal information
5. **TODO**: Add your project details
6. **TODO**: Customize colors and styles
7. **TODO**: Add profile images
8. **TODO**: Deploy to GitHub Pages

## 💡 Enhancement Ideas

- Add a blog section with Markdown support
- Include a downloadable resume/CV
- Add dark mode toggle
- Create detailed project case studies
- Add testimonials section
- Integrate with a contact form service
- Add animation libraries (Framer Motion, AOS)
- Implement RSS feed for blog

## 📚 Resources

- [Astro Documentation](https://docs.astro.build)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [GitHub Pages Deployment](https://docs.github.com/en/pages)

## 🤝 Need Help?

- Check the Astro docs: https://docs.astro.build
- Tailwind CSS guide: https://tailwindcss.com
- GitHub Pages docs: https://pages.github.com

---

**Made with ❤️ using Astro & Tailwind CSS**
