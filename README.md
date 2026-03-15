# Asma Khalil — Research Portfolio

Personal research portfolio: immunology, cancer biology, neuroengineering (NYUAD '26).

## Deploy on GitHub Pages

1. **Create a new repository** on GitHub (e.g. `portfolio` or `asma-khalil`).

2. **Initialize git and push** (from this folder in Terminal):
   ```bash
   cd /Users/ashraf/Documents/Portfolio_Asma
   git init
   git add index.html asma-portfolio.html Mitochondrial_image.png README.md
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your GitHub username and repo name.

3. **Turn on GitHub Pages**
   - Open the repo on GitHub → **Settings** → **Pages** (left sidebar).
   - Under **Source**, choose **Deploy from a branch**.
   - Branch: **main**, folder: **/ (root)**.
   - Click **Save**.

4. **View your site**  
   After a minute or two, it will be at:
   - **Project site:** `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`
   - **User/org site:** If the repo is named `YOUR_USERNAME.github.io`, then `https://YOUR_USERNAME.github.io/`

Keep `index.html` and `asma-portfolio.html` in sync when you change the portfolio; both point to `Mitochondrial_image.png` in the same folder.
