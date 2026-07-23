# Complete Deployment Guide - UAS Integra Costing Suite 2024

Comprehensive step-by-step guide to deploy your professional costing tool to GitHub Pages and make it live worldwide.

---

## 📋 What You're Deploying

**UAS Integra Costing Suite 2024** - A professional web application featuring:

- 🛠️ Implementation cost calculator
- 📊 Support tool pricing engine
- 📚 Project repository & history
- 💾 Local data persistence
- 🎨 Professional UI (Plus Jakarta Sans typography)
- 📱 Mobile responsive design

---

## ✅ Prerequisites

- ✓ GitHub account (free at https://github.com/signup)
- ✓ These 6 files ready:
  - `index.html` (main application)
  - `README.md` (documentation)
  - `QUICK_START.md` (quick guide)
  - `DEPLOYMENT_GUIDE.md` (this file)
  - `LICENSE` (MIT)
  - `.gitignore` (git config)

---

## 🚀 STEP 1: Create GitHub Repository

### Method A: Via GitHub Website (Easiest)

1. **Sign In**
   - Go to https://github.com and login

2. **Create New Repository**
   - Click the "+" icon (top-right)
   - Select "New repository"

3. **Configure Repository**
   - **Repository name:** `uas-integra-costing-suite`
   - **Description:** Professional costing tool for Integra UAS
   - **Visibility:** ✓ Public (required for free GitHub Pages)
   - **Initialize:** Leave unchecked (we'll add files manually)
   - Click **"Create repository"**

4. **Note the Repository URL**
   - HTTP: `https://github.com/YOUR_USERNAME/uas-integra-costing-suite`
   - SSH: `git@github.com:YOUR_USERNAME/uas-integra-costing-suite.git`

---

## 📁 STEP 2: Prepare Your Files

### Local Setup

1. **Create project folder**
   ```bash
   mkdir uas-integra-costing-suite
   cd uas-integra-costing-suite
   ```

2. **Add all 6 files** to this folder:
   ```
   uas-integra-costing-suite/
   ├── index.html
   ├── README.md
   ├── QUICK_START.md
   ├── DEPLOYMENT_GUIDE.md
   ├── LICENSE
   └── .gitignore
   ```

3. **Verify folder structure**
   - Ensure `index.html` is in the root directory
   - All files should be at the same level (no subfolders)

---

## 🚀 STEP 3: Upload Files to GitHub

### Option A: Via GitHub Web Interface (Simplest - No Git Required)

1. **Go to your repository**
   - Navigate to `https://github.com/YOUR_USERNAME/uas-integra-costing-suite`

2. **Upload files**
   - Click **"Add file"** → **"Upload files"**
   - Drag & drop all 6 files into the upload area
   - Or click **"choose your files"** to select them

3. **Commit**
   - Add message: `Initial commit: Add costing suite application`
   - Select **"Commit directly to main branch"**
   - Click **"Commit changes"**

✅ **Files are now on GitHub!**

---

### Option B: Using Git Command Line

1. **Navigate to folder**
   ```bash
   cd uas-integra-costing-suite
   ```

2. **Initialize Git repository**
   ```bash
   git init
   ```

3. **Add all files**
   ```bash
   git add .
   ```

4. **Create initial commit**
   ```bash
   git commit -m "Initial commit: Add costing suite application"
   ```

5. **Add remote repository**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/uas-integra-costing-suite.git
   ```
   
   Replace `YOUR_USERNAME` with your actual GitHub username

6. **Push to GitHub**
   ```bash
   git branch -M main
   git push -u origin main
   ```

   If prompted for credentials:
   - **Username:** Your GitHub username
   - **Password:** Your personal access token (NOT your GitHub password)

   **To create a Personal Access Token:**
   - Go to GitHub Settings → Developer settings → Personal access tokens
   - Click "Generate new token"
   - Select scopes: `repo` (full control of private repositories)
   - Copy the token and use it as your password
   - Save the token in a secure place

✅ **Files are now on GitHub!**

---

### Option C: Using GitHub Desktop

1. **Install GitHub Desktop**
   - Download from https://desktop.github.com/

2. **Create new repository**
   - Click "Create a new repository"
   - **Name:** `uas-integra-costing-suite`
   - **Local path:** Choose a folder on your computer
   - Click "Create Repository"

3. **Copy files into folder**
   - Move all 6 files into the repository folder

4. **Commit changes**
   - GitHub Desktop will detect new files
   - Add **Summary:** "Initial commit: Add costing suite"
   - Click "Commit to main"

5. **Publish to GitHub**
   - Click "Publish repository"
   - Click "Publish"

✅ **Files are now on GitHub!**

---

## 🌐 STEP 4: Enable GitHub Pages

### Configure Pages Settings

1. **Go to Repository Settings**
   - Navigate to `https://github.com/YOUR_USERNAME/uas-integra-costing-suite/settings`
   - Or click **Settings** tab in your repository

2. **Navigate to Pages**
   - In left sidebar, click **"Pages"**

3. **Configure Build & Deployment**
   - **Source** section:
     - **Branch:** Select `main` (or `master` if that's your default)
     - **Folder:** Select `/ (root)`
   - Click **"Save"**

4. **Wait for Deployment**
   - GitHub will start building your site (usually 1-3 minutes)
   - You'll see a message: "Your site is published at..."
   - The URL will be: `https://YOUR_USERNAME.github.io/uas-integra-costing-suite`

---

## ✨ STEP 5: Verify Your Live Site

1. **Wait 2-3 minutes**
   - GitHub needs time to process your site

2. **Access your URL**
   - Visit: `https://YOUR_USERNAME.github.io/uas-integra-costing-suite`
   - Replace `YOUR_USERNAME` with your GitHub username

3. **Test functionality**
   - ✓ Page loads without errors
   - ✓ Both tools are accessible (Implementation & Support)
   - ✓ Calculations work correctly
   - ✓ Data saves locally
   - ✓ Export functions work

4. **Bookmark it**
   - Save to your browser bookmarks
   - Share with your team

---

## 📊 STEP 6: Use Your Costing Tool

### Implementation Tool

1. **Select Scenario**
   - Choose location: Metro Manila, Nearby, or Far provinces

2. **Enter Project Details**
   - Assign engineers by level
   - Input estimated days
   - Add additional costs if needed

3. **Select PPE** (if applicable)
   - Check required items
   - Costs calculate automatically

4. **Save Estimate**
   - Click "Save to Repository"
   - Estimate stores in project history

### Support Tool

1. **Choose Support Level**
   - Select appropriate tier

2. **Configure Details**
   - Adjust rates or duration if needed

3. **Review Inclusions**
   - See what's included in package

4. **Save & Export**
   - Save for future reference

### Repository

1. **View All Projects**
   - Access repository tab
   - See all saved estimates

2. **Filter Projects**
   - Filter by type (Implementation/Support)
   - Search for specific projects

3. **Edit/Delete**
   - Modify existing estimates
   - Archive old projects

---

## 🔄 STEP 7: Make Updates

### Update Billing Rates

1. **Edit index.html**
   - Via GitHub web editor:
     - Click the pencil icon ✏️ on `index.html`
     - Find rate variables (search for "ASSOC_MONTH", "PROF_MONTH", etc.)
     - Update values as needed
     - Scroll to bottom and click "Commit changes"

2. **Changes go live**
   - Refresh your browser in 1-2 minutes
   - New rates are active

### Add New PPE Items

1. **Edit HTML**
   - Open index.html in editor
   - Find PPE section
   - Add new items following existing format

2. **Commit & Deploy**
   - GitHub automatically redeploys
   - Changes visible within 2 minutes

---

## 🌍 STEP 8: Share with Your Team

### Share the Live Link

```
Your costing tool is live at:
https://YOUR_USERNAME.github.io/uas-integra-costing-suite
```

### Email Template

```
Subject: 🚀 UAS Integra Costing Suite - Now Live

Hi Team,

Our new professional costing tool is now available:

🔗 https://YOUR_USERNAME.github.io/uas-integra-costing-suite

✨ Features:
• Implementation cost calculator
• Support tool pricing
• Project repository
• Real-time calculations
• Works on mobile devices
• No installation needed

Just open the link in your browser and start creating estimates!

Questions? See README.md or DEPLOYMENT_GUIDE.md

Thanks!
```

---

## 🔍 STEP 9: Monitor Your Site

### Check Deployment Status

1. **Go to Deployments**
   - Repository → Deployments (on the right sidebar)
   - Or: https://github.com/YOUR_USERNAME/uas-integra-costing-suite/deployments

2. **View github-pages Deployment**
   - Click latest deployment
   - See status: ✅ Active
   - View deployment history

3. **View Page Build Logs**
   - Click Actions tab
   - Select "pages build and deployment"
   - See detailed build logs

### Troubleshooting Deployments

| Issue | Solution |
|-------|----------|
| 404 Error | Wait 5 minutes, refresh browser with Ctrl+Shift+R |
| Blank page | Check browser console (F12), look for errors |
| Old version showing | Clear browser cache and localStorage |
| Files not found | Verify all files are in root directory |

---

## 🔒 Security Best Practices

✅ **Keep it Public** - Repository must be public for free GitHub Pages  
✅ **No Secrets** - Don't commit API keys or sensitive data  
✅ **Monitor Updates** - Watch GitHub security alerts  
✅ **Regular Backups** - Export project data periodically  
✅ **Secure Sharing** - Only share link with authorized team members  

---

## 📈 Advanced: Custom Domain

If you want to use a custom domain:

1. **Go to Pages Settings**
2. **Custom Domain** section
3. Enter your domain (e.g., costing.integrauas.com)
4. Follow GitHub's DNS configuration instructions
5. Update domain DNS records
6. Verify domain ownership

---

## 🐛 Troubleshooting

### Site Not Loading?

```
❌ 404 Error
✓ Wait 5 minutes for deployment
✓ Hard refresh: Ctrl+Shift+R
✓ Check Settings → Pages to verify URL
✓ Ensure repository is public
```

### Data Not Saving?

```
❌ Estimates disappear on reload
✓ Check if localStorage is enabled
✓ Clear browser cache
✓ Try private/incognito window
✓ Try different browser
```

### Changes Not Appearing?

```
❌ Updated file but old version shows
✓ Wait 2-3 minutes for redeploy
✓ Hard refresh: Ctrl+Shift+R
✓ Check Actions tab for deploy status
```

### Files Not Uploading?

```
❌ GitHub shows "failed to upload"
✓ Check file sizes (index.html should be ~1.2MB)
✓ Ensure .gitignore is plain text
✓ Try uploading 3 files at a time
✓ Check internet connection
```

---

## 📞 Support & Help

| Need | Contact |
|------|---------|
| **GitHub Issues** | github.com/YOUR_USERNAME/uas-integra-costing-suite/issues |
| **GitHub Docs** | https://docs.github.com/en/pages |
| **Integra UAS** | technical@integrauas.com |
| **Questions?** | See README.md or QUICK_START.md |

---

## ✅ Deployment Checklist

- [ ] GitHub account created
- [ ] Repository created and set to public
- [ ] All 6 files uploaded to root directory
- [ ] GitHub Pages enabled
- [ ] Site deployed (green checkmark)
- [ ] Live URL tested and working
- [ ] Functionality verified
- [ ] Team URL saved and shared
- [ ] Bookmarked for easy access
- [ ] Deployment guide saved

---

## 🎉 Success!

Your UAS Integra Costing Suite 2024 is now live and ready for use!

**Your Live URL:**
```
https://YOUR_USERNAME.github.io/uas-integra-costing-suite
```

**Next Steps:**
1. Share link with team
2. Start creating estimates
3. Save projects to repository
4. Export reports as needed
5. Update rates/settings as needed

---

**Questions?** See QUICK_START.md or README.md  
**Last Updated:** January 2024  
**Version:** 2024.1
