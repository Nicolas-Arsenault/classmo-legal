# Classmo Legal Pages - GitHub Pages Setup

This folder contains the privacy policy and terms of use for Classmo.

## Files

- `index.html` - Privacy Policy (Politique de confidentialité)
- `terms.html` - Terms of Use (Conditions d'utilisation)

## Setup Instructions

### 1. Create a new GitHub repository

```bash
# Navigate to this folder
cd classmo-legal

# Initialize git repo
git init

# Add files
git add .

# Commit
git commit -m "Add legal pages"
```

### 2. Create repository on GitHub

1. Go to https://github.com/new
2. Name it: `classmo-legal`
3. Keep it **Public** (required for free GitHub Pages)
4. Don't initialize with README (you already have files)
5. Click "Create repository"

### 3. Push to GitHub

```bash
git remote add origin https://github.com/Nicolas-Arsenault/classmo-legal.git
git branch -M main
git push -u origin main
```

### 4. Enable GitHub Pages

1. Go to your repo: https://github.com/Nicolas-Arsenault/classmo-legal
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under "Source", select **Deploy from a branch**
5. Select branch: **main**
6. Select folder: **/ (root)**
7. Click **Save**

### 5. Wait for deployment

- GitHub will build and deploy your site
- This takes 1-2 minutes
- You'll see a green checkmark when done

### 6. Your URLs

Once deployed, your pages will be available at:

- Privacy Policy: `https://nicolas-arsenault.github.io/classmo-legal/`
- Terms of Use: `https://nicolas-arsenault.github.io/classmo-legal/terms.html`

## Updating the Pages

To update the pages:

1. Edit `index.html` or `terms.html`
2. Commit and push:
   ```bash
   git add .
   git commit -m "Update legal pages"
   git push
   ```
3. GitHub Pages will automatically redeploy

## App Store Submission

When submitting to the App Store, use these URLs:

- Privacy Policy: `https://nicolas-arsenault.github.io/classmo-legal/`
- Terms of Use: `https://nicolas-arsenault.github.io/classmo-legal/terms.html`
