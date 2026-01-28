# 🚀 GitHub Pages Deployment Guide

Follow these simple steps to publish your Mood Palette tool on GitHub Pages.

## Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com)
2. Click "Sign up" (top right)
3. Follow the registration process
4. Verify your email address

## Step 2: Create a New Repository
1. Click the **"+"** icon (top right) → **"New repository"**
2. Fill in the details:
   - **Repository name**: `mood-palette` (or any name you like)
   - **Description**: "A web tool for extracting color palettes from images"
   - **Public** (must be public for free GitHub Pages)
   - ✅ Check "Add a README file"
3. Click **"Create repository"**

## Step 3: Upload Your Files
1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop these two files:
   - `mood-palette.html`
   - `README.md`
3. Scroll down and click **"Commit changes"**

## Step 4: Rename HTML File (Important!)
GitHub Pages looks for `index.html` as the main file:
1. Click on `mood-palette.html` in your repository
2. Click the pencil icon (✏️) to edit
3. Change the filename from `mood-palette.html` to `index.html`
4. Scroll down and click **"Commit changes"**

## Step 5: Enable GitHub Pages
1. Go to **Settings** tab (in your repository)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select:
   - Branch: **main** (or **master**)
   - Folder: **/ (root)**
4. Click **"Save"**

## Step 6: Wait and View Your Site! 🎉
1. GitHub will take 1-3 minutes to build your site
2. Refresh the Pages settings page
3. You'll see a message: **"Your site is live at https://yourusername.github.io/mood-palette/"**
4. Click the URL to view your published tool!

---

## 🔄 Updating Your Site

To make changes later:
1. Edit the `index.html` file directly on GitHub (click the pencil icon)
2. Or upload a new version using "Add file" → "Upload files"
3. Changes go live automatically in 1-3 minutes!

---

## 📝 Pro Tips

### Custom Domain (Optional)
Want to use your own domain like `moodpalette.com`?
1. Buy a domain from Namecheap, Google Domains, etc.
2. In GitHub Settings → Pages, add your custom domain
3. Update your domain's DNS settings (GitHub provides instructions)

### Add a Nice URL to README
After deployment, update your README.md:
1. Find the line: `Visit the live demo: [Your GitHub Pages URL will go here]`
2. Replace it with your actual URL: `Visit the live demo: https://yourusername.github.io/mood-palette/`

### Share Your Project
Once live, share your URL:
- ✅ Add it to your portfolio
- ✅ Share on social media
- ✅ Add to your resume
- ✅ Show potential clients/employers

---

## ❓ Troubleshooting

**Site not showing up?**
- Wait 3-5 minutes after enabling Pages
- Make sure your HTML file is named `index.html`
- Check that repository is public
- Hard refresh your browser (Ctrl+Shift+R or Cmd+Shift+R)

**404 Error?**
- Confirm the branch is set correctly in Pages settings
- Make sure `index.html` is in the root folder

**Need help?**
- Check [GitHub Pages documentation](https://docs.github.com/en/pages)
- Ask in GitHub community discussions

---

## 🎊 Success!

Your Mood Palette tool is now live and accessible to anyone in the world!

**Next Steps:**
- Share your URL with friends and colleagues
- Add the project to your portfolio
- Keep the repository updated with improvements
- Consider adding more features!

**Your URL format will be:**
```
https://[your-github-username].github.io/mood-palette/
```

Example: If your username is "johndoe", your URL will be:
```
https://johndoe.github.io/mood-palette/
```
