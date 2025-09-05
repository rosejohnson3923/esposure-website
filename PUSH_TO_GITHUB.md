# Push Esposure.gg to GitHub

## Quick Steps

### 1. Create GitHub Repository
Go to: https://github.com/new

**Settings:**
- Repository name: `esposure-website`
- Description: "Esposure.gg - Enterprise EdTech infrastructure platform"
- Public or Private: Your choice
- **DO NOT** initialize with README, .gitignore, or license

### 2. Push Your Code

**Option A: Standard Push**
```bash
cd C:\Users\rosej\Documents\Projects\esposure-website
git push -u origin master
```

When prompted:
- Username: `rosejohnson3923`
- Password: Your GitHub Personal Access Token

**Option B: Direct with Token**
```bash
cd C:\Users\rosej\Documents\Projects\esposure-website
git push https://rosejohnson3923:YOUR_TOKEN@github.com/rosejohnson3923/esposure-website.git master
```

Replace `YOUR_TOKEN` with your actual GitHub token.

### 3. Repository URL
Your repository will be at:
https://github.com/rosejohnson3923/esposure-website

## Netlify Configuration

Once pushed to GitHub:

**Build Settings:**
- Branch: `master`
- Build command: (leave empty)
- Publish directory: `.`

**Domain:**
- Custom domain: esposure.gg
- HTTPS: Automatic

## Status Check

Remote is already configured:
- origin: https://github.com/rosejohnson3923/esposure-website.git

Ready to push! 🚀