# Simple Research Website - Deployment Instructions

## What You're Getting

A clean, simple website with:
- **Landing page** (`index.html`) with your 2 research projects
- **2 clickable project pages** (currently showing "Content coming soon...")
- **Clean styling** similar to the Python Causality Handbook
- **No build process** - just upload and it works!

## Files

```
simple-site/
├── index.html               # Main landing page
├── alternative-proteins.html # Research project 1 (placeholder)
├── sign-language.html       # Research project 2 (placeholder)
└── style.css                # All the styling
```

## Deploy to GitHub Pages (Takes 2 Minutes!)

### Step 1: Upload Files

1. Go to your repository: https://github.com/gabby-bui/gabbybuiresearch.github.io
2. **Delete everything** currently in the repo (or move to a backup branch)
3. Click "Add file" → "Upload files"
4. Drag and drop ALL 4 files:
   - `index.html`
   - `alternative-proteins.html`
   - `sign-language.html`
   - `style.css`
5. Commit: "Simple site with research links"

### Step 2: Configure GitHub Pages

1. Go to Settings → Pages
2. Source: **Deploy from a branch**
3. Branch: **main** / **(root)**
4. Click Save

### Step 3: Visit Your Site!

Wait 1-2 minutes, then visit:
**https://gabby-bui.github.io/gabbybuiresearch.github.io/**

That's it! No build process, no Actions needed.

## How to Add Content Later

When you're ready to add content to a project page:

1. Click on the HTML file (e.g., `alternative-proteins.html`)
2. Click the pencil icon (Edit)
3. Replace the "Content coming soon..." section with your content
4. Use simple HTML like:
   ```html
   <h2>Background</h2>
   <p>Your text here...</p>
   
   <h2>Methodology</h2>
   <p>More text...</p>
   ```
5. Commit changes
6. Your site updates automatically in 1-2 minutes!

## Customization

### Update Your Email
In `index.html`, line in footer:
```html
<a href="mailto:your-email@example.com">your-email@example.com</a>
```

### Change Colors
In `style.css`, the main colors are:
- Blue accent: `#007bff` 
- Dark text: `#2c3e50`
- Light background: `#f8f9fa`

Just search and replace to change the color scheme!

### Add More Projects
Copy the project card in `index.html`:
```html
<div class="project-card">
    <h3><a href="new-project.html">New Project Title</a></h3>
    <p class="project-type">Project Type</p>
    <p>Description here...</p>
    <div class="tags">
        <span class="tag">Tag1</span>
        <span class="tag">Tag2</span>
    </div>
</div>
```

## Why This Approach?

- ✅ **Simple**: No complex build systems
- ✅ **Fast**: Upload and it works immediately
- ✅ **Easy to edit**: Just edit HTML files directly on GitHub
- ✅ **Clean design**: Professional look without complexity
- ✅ **Mobile responsive**: Works great on phones/tablets

## Need to Go Back to Jupyter Book?

If you later want the more complex Jupyter Book setup with code execution, you can always switch back. But this gives you a working site RIGHT NOW that you can easily update.
