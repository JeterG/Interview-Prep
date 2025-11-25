# Quick Deployment Guide - GitHub Pages

## 🚀 Fastest Way to Deploy (5 minutes)

### Step 1: Extract the ZIP
1. Download `study-guide-website.zip`
2. Extract all files to a folder

### Step 2: Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `interview-study-guide` (or any name you want)
3. Make it **Public**
4. **DO NOT** check "Add README" (we already have one)
5. Click "Create repository"

### Step 3: Upload Files
**Option A: Drag and Drop (Easiest)**
1. On your new repo page, click "uploading an existing file"
2. Drag ALL the HTML files and README.md into the upload area
3. Write commit message: "Add interview study guide"
4. Click "Commit changes"

**Option B: Git Command Line**
```bash
cd path/to/extracted/files
git init
git add .
git commit -m "Add interview study guide"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/interview-study-guide.git
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" (top menu)
3. Click "Pages" (left sidebar)
4. Under "Source":
   - Branch: Select "main"
   - Folder: Select "/ (root)"
5. Click "Save"
6. Wait 1-2 minutes

### Step 5: Access Your Site! 🎉
Your site will be live at:
```
https://YOUR_USERNAME.github.io/interview-study-guide/
```

Example: If your GitHub username is `jeterg`, your site will be at:
```
https://jeterg.github.io/interview-study-guide/
```

## 📱 Share Your Site
After deployment, you can:
- Bookmark the URL for easy access
- Access from any device (phone, tablet, laptop)
- Share with friends or mentors
- Access offline (GitHub Pages caches files)

## ⚡ Quick Tips
- **First visit may take 1-2 minutes** to build
- If you don't see changes, try **hard refresh**: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- To update content: Just commit new files to the repo
- GitHub Pages automatically rebuilds when you push changes

## 🔗 Useful Links
- Your repo: `https://github.com/YOUR_USERNAME/interview-study-guide`
- Your site: `https://YOUR_USERNAME.github.io/interview-study-guide/`
- GitHub Pages docs: https://pages.github.com/

## ❓ Troubleshooting

**Site not loading?**
- Wait 2-3 minutes after enabling Pages
- Check Settings → Pages shows green checkmark
- Clear browser cache (Ctrl+Shift+Delete)

**404 Error?**
- Make sure `index.html` is in the root folder
- Verify Pages is enabled and pointing to "main" branch
- Check repository is Public, not Private

**Changes not showing?**
- Hard refresh: Ctrl+Shift+R or Cmd+Shift+R
- Wait 1-2 minutes for GitHub to rebuild
- Clear browser cache

## 🎯 You're All Set!
Now you can study from anywhere with internet access. Good luck with your interview! 🍀
