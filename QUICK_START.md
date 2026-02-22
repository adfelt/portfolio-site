# Quick Start Guide - Andrew Felt Portfolio

## Immediate Next Steps

### 1. Install and Run Locally

```bash
cd andrewfelt-portfolio
npm install
npm run dev
```

Visit `http://localhost:4321` to see your site!

### 2. Update These Files First

#### **Priority Updates (Do These First):**

**src/components/Hero.astro**
- Line 8-9: Update your intro text
- Line 11-14: Personalize your description

**src/components/Footer.astro**
- Line 17-19: Add your GitHub URL
- Line 20-22: Add your LinkedIn URL  
- Line 23: Update your email

**src/components/Projects.astro**
- Lines 4-39: Replace with your actual projects
- Update GitHub links, project links, titles, and descriptions

**src/components/Contact.astro**
- Line 23: Update your email
- Line 35: Add your LinkedIn URL
- Line 47: Add your GitHub URL

#### **Secondary Updates:**

**src/components/About.astro**
- Lines 24-30: Customize your "About Me" story
- Lines 3-21: Update skills to match your actual skillset

**src/pages/blog.astro**
- Lines 5-23: Update blog post titles and excerpts (or remove until you write posts)

### 3. Add Your Links

Find and replace throughout the project:
- `yourusername` → Your actual GitHub/LinkedIn username
- `hello@andrewfelt.com` → Your actual email
- Update Felt Enterprises URL if different

### 4. Optional Enhancements

**Add Resume:**
- Place `resume.pdf` in the `/public/` folder

**Update Headshot Later:**
- Replace `/public/headshot.jpg` with a new photo if desired

**Customize Colors (If Desired):**
- Edit color variables in `src/styles/global.css` (lines 2-9)

### 5. Deploy When Ready

**Option A: Vercel (Recommended)**
1. Push code to GitHub
2. Import project at vercel.com
3. Deploy automatically
4. Add custom domain: andrewfelt.com

**Option B: Netlify**
1. Push code to GitHub  
2. Import project at netlify.com
3. Deploy automatically
4. Add custom domain: andrewfelt.com

## Common Questions

**Q: How do I add more projects?**
A: Edit the `projects` array in `src/components/Projects.astro` and add new objects following the same format.

**Q: Can I change the colors?**
A: Yes! Edit the CSS variables in `src/styles/global.css` (look for `:root` section)

**Q: How do I add blog posts?**
A: For now, update the array in `src/pages/blog.astro`. Later, you can create individual `.md` files or use a CMS.

**Q: How do I add GitHub integration?**
A: You can fetch repos using the GitHub API. Create a new component that calls `https://api.github.com/users/YOUR_USERNAME/repos`

**Q: The site won't build. What do I do?**
A: Make sure you have Node.js 18+ installed. Run `npm install` first, then `npm run dev`

## File Structure Reference

```
Key files to customize:
├── src/components/
│   ├── Hero.astro       ← Your intro
│   ├── Projects.astro   ← Your work
│   ├── About.astro      ← Your story
│   ├── Contact.astro    ← Your links
│   └── Footer.astro     ← Social links
├── src/pages/
│   ├── index.astro      ← Homepage (uses components)
│   └── blog.astro       ← Blog listing
└── public/
    ├── headshot.jpg     ← Your photo
    └── resume.pdf       ← Add your resume here
```

## Color Palette Quick Reference

```css
Navy:    #0A2540  /* Primary color */
Coral:   #FF5757  /* Accent/CTA buttons */
Gold:    #F39C12  /* Secondary accent */
Light:   #E8EDF2  /* Backgrounds */
```

Good luck! You've got a solid foundation. Focus on content first, polish later.
