# Bitcoin Economics Website

A collection of educational content about monetary systems, the Cantillon Effect, and Bitcoin economics.

## 📄 Pages

- **index.html** - The Cantillon Effect & Bitcoin's Deflationary Future
- **lending-rates.html** - Lending Rates in a Bitcoin World

## 🚀 Deploying to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right and select **New repository**
3. Name your repository (e.g., `bitcoin-economics` or `mywebsite`)
4. Choose **Public** (required for free GitHub Pages)
5. **Do NOT** initialize with README, .gitignore, or license (we already have files)
6. Click **Create repository**

### Step 2: Initialize Git in Your Project

Open Terminal in this folder and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Create your first commit
git commit -m "Initial commit: Bitcoin economics website"
```

### Step 3: Connect to GitHub and Push

Replace `YOUR-USERNAME` and `YOUR-REPO-NAME` with your actual GitHub username and repository name:

```bash
# Add GitHub as remote
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Click **Pages** in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Under **Branch**, select **main** and **/ (root)**
6. Click **Save**

### Step 5: Access Your Website

After a few minutes, your site will be live at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

Your pages will be available at:
- `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/` (index.html - Cantillon Effect)
- `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/lending-rates.html` (Lending Rates)

## 🔄 Updating Your Website

Whenever you make changes:

```bash
# Stage your changes
git add .

# Commit with a message
git commit -m "Update content"

# Push to GitHub
git push
```

GitHub Pages will automatically rebuild your site (takes 1-2 minutes).

## 💡 Quick Commands Reference

```bash
# Check status
git status

# See what changed
git diff

# View commit history
git log --oneline

# Undo uncommitted changes
git checkout -- filename.html
```

## 🎨 Customization Tips

- Edit HTML files directly to update content
- Modify CSS files to change styling
- Add new pages by creating additional HTML files
- Link between pages using relative paths

## 📱 Testing Locally

Simply open the HTML files in your browser:
- Double-click `index.html` or `lending-rates.html`
- Or use a local server with Python:
  ```bash
  python3 -m http.server 8000
  ```
  Then visit `http://localhost:8000`

## 🌐 Custom Domain (Optional)

To use a custom domain:
1. Add a file named `CNAME` with your domain (e.g., `www.yourdomain.com`)
2. Configure your domain's DNS settings to point to GitHub Pages
3. See [GitHub's custom domain documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

## 📝 License

Feel free to use and modify this content for educational purposes.
