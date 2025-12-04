# 🚀 Deployment Guide - Vercel

Follow these simple steps to deploy your ebook to Vercel.

## Prerequisites

✅ Git repository initialized (DONE)
✅ All files committed (DONE)
✅ index.html created (DONE)

## Deployment Steps

### Option 1: Deploy via Vercel Website (Easiest)

1. **Go to Vercel**
   - Visit: https://vercel.com
   - Click "Sign Up" or "Login"
   - Choose "Continue with Email"
   - Enter: mahunivictor13@gmail.com

2. **Import Project**
   - Click "Add New..." → "Project"
   - Click "Import Git Repository"
   - If this is your first time, you'll need to connect GitHub first

3. **Connect GitHub (First Time Only)**
   - Click "Continue with GitHub"
   - Authorize Vercel
   - Create a new repository for this project

4. **Push to GitHub First**
   Open a terminal/command prompt and run these commands:

   ```bash
   cd C:\Users\HomePC\Documents\ebook

   # Create a new repository on GitHub first (via github.com)
   # Then run these commands:

   git remote add origin YOUR_GITHUB_REPO_URL
   git branch -M main
   git push -u origin main
   ```

5. **Back to Vercel**
   - Import your GitHub repository
   - Click "Deploy"
   - Wait 30-60 seconds
   - Done! You'll get a URL like: https://your-project.vercel.app

### Option 2: Deploy via Vercel CLI (For Advanced Users)

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel**
   ```bash
   vercel login mahunivictor13@gmail.com
   ```

3. **Deploy**
   ```bash
   cd C:\Users\HomePC\Documents\ebook
   vercel
   ```

4. **Follow the prompts**
   - Set up and deploy? Yes
   - Which scope? Your account
   - Link to existing project? No
   - Project name? (press Enter for default)
   - Directory? ./
   - Auto-detected settings? Yes

5. **Deploy to Production**
   ```bash
   vercel --prod
   ```

## After Deployment

Your ebook will be available at a URL like:
- https://chido-forex-academy.vercel.app

You can:
- Share this URL with clients
- Set up a custom domain (in Vercel settings)
- Update the site by pushing to GitHub (auto-deploys)

## Troubleshooting

**Images not showing?**
- Check that the `public` folder is in the repository
- Verify paths in index.html are correct (public/assets/images/...)

**Need help?**
- Vercel Documentation: https://vercel.com/docs
- Support: support@vercel.com

## Custom Domain (Optional)

1. Go to your project in Vercel
2. Settings → Domains
3. Add your custom domain
4. Follow DNS configuration instructions

---

Need help? Contact Vercel support or check their documentation!
