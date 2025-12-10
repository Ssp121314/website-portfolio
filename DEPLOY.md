# 🚀 How to Deploy to GitHub Pages

## Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** icon in the top right → **"New repository"**
3. Repository name: `sanketpophale.github.io` (for custom domain) OR any name you prefer
4. Make it **Public**
5. **DO NOT** initialize with README, .gitignore, or license
6. Click **"Create repository"**

## Step 2: Push Your Code

Run these commands in your terminal (in the website folder):

```bash
# Add remote repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/sanketpophale.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select **"main"** branch
5. Click **Save**

## Step 4: Your Website is Live! 🎉

Your website will be available at:
- `https://YOUR_USERNAME.github.io/sanketpophale.github.io` (if custom repo name)
- OR `https://YOUR_USERNAME.github.io` (if repo named `YOUR_USERNAME.github.io`)

**Note:** It may take 1-2 minutes for the site to go live after enabling Pages.

## 🔄 Updating Your Website

Whenever you make changes:

```bash
git add .
git commit -m "Update website"
git push
```

Changes will be live in 1-2 minutes!

## 📝 Custom Domain (Optional)

If you have a custom domain:

1. In GitHub Pages settings, add your domain
2. Create a `CNAME` file in your repository with your domain name
3. Update DNS records as instructed by GitHub

---

**Need Help?** Check GitHub Pages documentation: https://docs.github.com/en/pages

