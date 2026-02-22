# Andrew Felt - Portfolio Website

A modern, sleek portfolio website built with Astro featuring a bold Navy & Coral color scheme.

## 🚀 Features

- **Fast & Modern**: Built with Astro for optimal performance
- **Responsive Design**: Looks great on all devices
- **Bold Professional Aesthetic**: Navy & Coral color scheme that stands out
- **Easy to Customize**: Well-organized components and clear structure
- **SEO Friendly**: Semantic HTML and proper meta tags
- **Blog Ready**: Includes blog structure for writing

## 🎨 Color Scheme

- **Primary Navy**: `#0A2540` - Deep, professional navy
- **Accent Coral**: `#FF5757` - Vibrant, attention-grabbing coral
- **Accent Gold**: `#F39C12` - Warm secondary accent
- **Neutral Light**: `#E8EDF2` - Soft background gray
- **Background**: `#FAFBFC` - Clean white with slight warmth

## 📁 Project Structure

```
/
├── public/
│   └── headshot.jpg          # Your professional headshot
├── src/
│   ├── components/
│   │   ├── Header.astro      # Navigation header
│   │   ├── Hero.astro        # Homepage hero section
│   │   ├── Projects.astro    # Featured projects showcase
│   │   ├── About.astro       # About section with skills
│   │   ├── Contact.astro     # Contact section with links
│   │   └── Footer.astro      # Site footer
│   ├── layouts/
│   │   └── Layout.astro      # Base layout template
│   ├── pages/
│   │   ├── index.astro       # Homepage
│   │   └── blog.astro        # Blog listing page
│   └── styles/
│       └── global.css        # Global styles and color variables
```

## 🛠️ Customization Guide

### 1. Update Personal Information

**In `src/components/Hero.astro`:**
- Update the intro text and description
- Modify button links if needed

**In `src/components/Projects.astro`:**
- Replace placeholder projects with your actual projects
- Update GitHub links, project links, and descriptions
- Add/remove projects as needed

**In `src/components/About.astro`:**
- Customize the "About Me" narrative
- Update skills in each category
- Change email and resume links

**In `src/components/Contact.astro`:**
- Update email address
- Add your LinkedIn and GitHub URLs
- Update quick links

**In `src/components/Footer.astro`:**
- Update social media links
- Modify footer sections as needed

### 2. Update Links Throughout

Search and replace these placeholder links:
- `yourusername` → Your actual GitHub/LinkedIn username
- `hello@andrewfelt.com` → Your email address
- `https://feltenterprises.com` → Your pressure washing site URL
- `/resume.pdf` → Path to your resume (add to `/public/`)

### 3. Add Your Resume

Place your resume PDF in the `/public/` folder as `resume.pdf`

### 4. Blog Posts

To add blog posts:
1. Update the `blogPosts` array in `src/pages/blog.astro`
2. Create individual blog post pages in `src/pages/blog/[slug].astro` (optional for now)

### 5. GitHub Integration (Coming Soon)

For dynamic GitHub repo display, you can:
- Use the GitHub API to fetch your repos
- Add a React component for interactive display
- Filter repos by topics/stars

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ installed
- npm or yarn

### Installation

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

The site will be available at `http://localhost:4321`

## 📦 Deployment

### Recommended: Vercel or Netlify

**Vercel:**
```bash
npm install -g vercel
vercel
```

**Netlify:**
```bash
npm install -g netlify-cli
netlify deploy --prod
```

Both platforms offer:
- Automatic deployments from Git
- Free SSL certificates
- Custom domain support
- Edge CDN distribution

### Custom Domain Setup

1. Deploy to your hosting platform
2. In your domain registrar (where you bought andrewfelt.com):
   - Add an A record pointing to your host's IP, or
   - Add a CNAME record pointing to your host's URL
3. Configure the custom domain in your hosting platform

## 🎯 Next Steps

### Phase 1 (Immediate)
- [ ] Update all personal information
- [ ] Replace placeholder links
- [ ] Add real project descriptions
- [ ] Write 2-3 blog posts
- [ ] Add resume PDF

### Phase 2 (Soon)
- [ ] Add GitHub API integration for dynamic project display
- [ ] Create individual blog post pages
- [ ] Add analytics (Vercel Analytics or Google Analytics)
- [ ] Implement contact form with email service

### Phase 3 (Future)
- [ ] Add interactive tools/web apps section
- [ ] Create case studies for major projects
- [ ] Add testimonials section
- [ ] Implement dark mode toggle

## 💡 Tips

- **Keep it simple**: Don't over-complicate. Focus on clear, impactful content.
- **Update regularly**: Keep projects and blog current to show you're active.
- **Tell stories**: People connect with narratives, not just lists of skills.
- **Show results**: Use numbers and outcomes in project descriptions.
- **Be authentic**: Let your personality show—it's what makes you memorable.

## 📝 License

This is your personal portfolio. Use it however you like!

---

Built with ❤️ using Astro
