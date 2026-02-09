# AI Consultancy Portfolio Website

A modern, responsive portfolio website for AI consultancy services.

## Quick Deploy to Vercel

### Method 1: Using Vercel CLI (Recommended)

1. **Install Vercel CLI** (if you haven't already):
   ```bash
   npm install -g vercel
   ```

2. **Navigate to the project folder**:
   ```bash
   cd ai-consultancy-site
   ```

3. **Login to Vercel**:
   ```bash
   vercel login
   ```
   - This will open a browser window
   - Login with your GitHub, GitLab, or Bitbucket account

4. **Deploy the website**:
   ```bash
   vercel
   ```
   - Press Enter to accept default settings
   - Your site will be deployed and you'll get a URL instantly!

5. **Deploy to production** (optional):
   ```bash
   vercel --prod
   ```

### Method 2: Using Vercel Dashboard (Easier for beginners)

1. **Go to [vercel.com](https://vercel.com)** and sign up/login

2. **Click "Add New..." → Project**

3. **Import your Git repository** OR **drag and drop this folder**
   - If using Git: Connect your GitHub/GitLab account and select the repo
   - If drag-and-drop: Just drag this entire folder into the upload area

4. **Configure project**:
   - Project Name: `ai-consultancy` (or whatever you want)
   - Framework Preset: Select "Other"
   - Root Directory: `./`
   - Build Command: Leave empty (it's static HTML)
   - Output Directory: Leave empty

5. **Click "Deploy"**

6. **Wait 30-60 seconds** and your site will be live!

### Method 3: Using GitHub + Vercel (Best for ongoing updates)

1. **Create a new GitHub repository**:
   - Go to github.com
   - Click "New repository"
   - Name it `ai-consultancy-site`
   - Don't initialize with README

2. **Push your code to GitHub**:
   ```bash
   cd ai-consultancy-site
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/ai-consultancy-site.git
   git push -u origin main
   ```

3. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "Add New..." → Project
   - Import your GitHub repository
   - Click "Deploy"

4. **Automatic updates**: Now whenever you push to GitHub, Vercel will auto-deploy!

## Custom Domain (Optional)

Once deployed, you can add a custom domain:

1. Go to your project in Vercel dashboard
2. Click "Settings" → "Domains"
3. Add your domain (e.g., `aiconsultancy.com`)
4. Follow DNS instructions to point your domain to Vercel

## Files Included

- `index.html` - Your portfolio website
- `vercel.json` - Vercel configuration
- `README.md` - This file

## Need Help?

- [Vercel Documentation](https://vercel.com/docs)
- [Vercel Support](https://vercel.com/support)
