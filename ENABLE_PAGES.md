# 🚀 Enable GitHub Pages - Step by Step Guide

## Your website is ready! Just need to enable GitHub Pages.

### 📍 Current Status:
✅ Code is pushed to GitHub  
✅ All files are in place  
❌ GitHub Pages needs to be enabled

---

## 🔧 Method 1: Enable via GitHub Website (Easiest)

### Step-by-Step Instructions:

1. **Go to your repository**
   - Visit: https://github.com/Ssp121314/website-portfolio

2. **Click on "Settings"**
   - It's in the top menu bar (next to "Code", "Issues", etc.)

3. **Find "Pages" in the left sidebar**
   - Scroll down in the left menu
   - Look under "Code and automation" section
   - Click on "Pages"

4. **Configure the source:**
   - Under "Source", you'll see a dropdown
   - Select: **"Deploy from a branch"**
   - Branch: Select **"main"**
   - Folder: Select **"/ (root)"**

5. **Click "Save"**
   - A green banner will appear saying "Your site is ready to be published"

6. **Wait 1-2 minutes**
   - GitHub will build your site
   - You'll see a message: "Your site is live at https://ssp121314.github.io/website-portfolio/"

7. **Visit your website!**
   - Go to: **https://ssp121314.github.io/website-portfolio/**

---

## 🔧 Method 2: Using GitHub Actions (Automatic)

I've created a GitHub Actions workflow file that will automatically deploy your site.

**Just push the workflow file and it will work automatically:**

```bash
git add .
git commit -m "Add GitHub Pages workflow"
git push
```

Then enable Pages in Settings → Pages → Source: "GitHub Actions"

---

## ❓ Troubleshooting

### If you still see 404:

1. **Check Settings → Pages**
   - Make sure "Deploy from a branch" is selected
   - Branch is set to "main"
   - Folder is "/ (root)"

2. **Wait a few minutes**
   - First deployment can take 2-5 minutes

3. **Check Actions tab**
   - Go to "Actions" in your repository
   - See if there are any build errors

4. **Verify files are in root**
   - Make sure `index.html` is in the root folder
   - Not in a subfolder

---

## 📝 Quick Checklist:

- [ ] Repository is public (or you have GitHub Pro)
- [ ] `index.html` is in the root directory
- [ ] Settings → Pages → Source is set to "main" branch
- [ ] Clicked "Save"
- [ ] Waited 2-3 minutes for build

---

## 🎉 Once Enabled:

Your website will be live at:
**https://ssp121314.github.io/website-portfolio/**

Any future pushes to the `main` branch will automatically update your website!

---

**Need help?** Check the GitHub Pages documentation: https://docs.github.com/en/pages

