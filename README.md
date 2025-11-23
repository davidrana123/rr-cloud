# Rural Root Cloud Tech Services And Training (RR Cloud)

Official website for RR Cloud - Cloud-ready products, built from the roots up.

## 🚀 Deploying to GitHub Pages

Follow these steps to deploy your website to GitHub Pages:

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **"+"** icon (top right) → **"New repository"**
3. Name it: `ruralrootcloud` (or any name you prefer)
4. Make it **Public**
5. **Do NOT** initialize with README (we already have files)
6. Click **"Create repository"**

### Step 2: Push Your Code to GitHub

Open PowerShell in this directory (`C:\RRCloud\Main Site`) and run these commands:

```powershell
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - RR Cloud website"

# Add your GitHub repository as remote (replace YOUR-USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR-USERNAME/ruralrootcloud.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** tab
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select **"Deploy from a branch"**
5. Under **"Branch"**, select **"main"** and **"/ (root)"**
6. Click **"Save"**

### Step 4: Access Your Website

After 2-3 minutes, your site will be live at:

```
https://YOUR-USERNAME.github.io/ruralrootcloud/
```

## 📁 Project Structure

```
Main Site/
├── index.html          # Main HTML file
├── style.css           # All styles (mobile-first, fully responsive)
├── logo/
│   └── rr logo.png    # Company logo
└── founder/
    ├── first.jpeg     # Vibhanshu Rana photo
    └── second.png     # David Singh Rana photo
```

## 🎨 Features

- ✅ Modern, clean, minimalist design
- ✅ Smart green color palette (#10B981)
- ✅ Fully responsive (mobile-first)
- ✅ No JavaScript - Pure HTML/CSS
- ✅ Premium founders section with powerful quotes
- ✅ Perfect card layouts on all devices
- ✅ Zero horizontal scroll
- ✅ Optimized for high conversion

## 📱 Supported Devices

- Small mobiles (320px+)
- Normal mobiles (360-430px)
- Large mobiles/Phablets (430-600px)
- Tablets (600-900px)
- Desktops (900px+)

## 🔧 Tech Stack

- HTML5
- CSS3 (Grid & Flexbox)
- Google Fonts (Inter)

## 📧 Contact

Email: ruralrootcloud@gmail.com

---

© 2025 Rural Root Cloud Tech Services And Training. All rights reserved.
