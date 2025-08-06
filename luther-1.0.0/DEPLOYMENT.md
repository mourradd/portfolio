# 🚀 Portfolio Website Deployment Guide

## Free Hosting Options

### 1. GitHub Pages (Recommended)

**Steps:**
1. Create a GitHub account at [github.com](https://github.com)
2. Create a new repository named `yourusername.github.io`
3. Push your code to GitHub:
   ```bash
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git branch -M main
   git push -u origin main
   ```
4. Go to repository Settings → Pages
5. Select "Deploy from a branch" → "main" branch
6. Your site will be live at `https://yourusername.github.io`

**Pros:** Free, professional domain, easy updates, version control

---

### 2. Netlify (Alternative)

**Steps:**
1. Go to [netlify.com](https://netlify.com) and sign up
2. Drag and drop your website folder to deploy
3. Get a free subdomain like `your-site.netlify.app`
4. Optionally connect your custom domain

**Pros:** Free tier, automatic deployments, custom domains

---

### 3. Vercel (Alternative)

**Steps:**
1. Go to [vercel.com](https://vercel.com) and sign up
2. Import your GitHub repository
3. Deploy automatically
4. Get a free subdomain like `your-site.vercel.app`

**Pros:** Fast, automatic deployments, great performance

---

### 4. Firebase Hosting

**Steps:**
1. Install Firebase CLI: `npm install -g firebase-tools`
2. Run `firebase login`
3. Run `firebase init hosting`
4. Deploy with `firebase deploy`

**Pros:** Google's infrastructure, fast CDN, custom domains

---

## Quick GitHub Pages Setup

Since you already have Git initialized, just follow these steps:

1. **Create GitHub Repository:**
   - Go to [github.com](https://github.com)
   - Click "New repository"
   - Name it `yourusername.github.io` (replace with your actual username)
   - Make it public
   - Don't initialize with README

2. **Connect and Push:**
   ```bash
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch
   - Click "Save"

4. **Your site will be live in a few minutes at:**
   `https://yourusername.github.io`

---

## Custom Domain (Optional)

If you want a custom domain like `moustafa.dev`:

1. **Buy a domain** from providers like:
   - Namecheap ($10-15/year)
   - GoDaddy ($10-15/year)
   - Google Domains ($12/year)

2. **For GitHub Pages:**
   - Add your domain in repository Settings → Pages
   - Update your DNS records as instructed

3. **For other platforms:**
   - Follow their custom domain setup guides

---

## File Structure Check

Make sure your `index.html` is in the root directory (which it is ✅)

---

## Next Steps

1. Choose your preferred hosting platform
2. Follow the setup steps above
3. Test your live website
4. Share your portfolio URL with potential employers!

---

## Troubleshooting

**If GitHub Pages doesn't work:**
- Check that your repository is public
- Ensure `index.html` is in the root directory
- Wait 5-10 minutes for deployment

**If images don't load:**
- Check that all image paths are correct
- Ensure all image files are committed to Git

**Need help?** Check the platform's documentation or ask in their community forums. 