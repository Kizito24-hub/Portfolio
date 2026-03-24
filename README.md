# Portfolio — publish on GitHub Pages

This is a minimal, responsive portfolio site you can publish with GitHub Pages. Replace placeholder links (`YOUR_USERNAME`, `YOUR_PROFILE`, `PROJECT-ONE`, etc.) and update content.

Quick publish steps (PowerShell):

```powershell
cd 'c:/Users/HP/OneDrive/Documents/Portfolio'
git init
git add .
git commit -m "Initial portfolio by assistant"
git branch -M main
git remote remove origin 2>$null; git remote add origin https://github.com/Kizito24-hub/Portfolio.git
git push -u origin main
```

Then on GitHub:
- Open the repository settings -> Pages
- Set the source to branch `main` and folder `/ (root)` and Save
- Your site will be published at `https://Kizito24-hub.github.io/Portfolio/`

Optional: create the repo and push using the GitHub CLI:

```powershell
gh repo create Kizito24-hub/Portfolio --public --source=. --remote=origin --push
```

Next steps:
- Replace links with your real LinkedIn and GitHub URLs.
- Update `index.html` project cards with real project descriptions and images.
- Ask me to push to GitHub (I can provide commands you can run) or to customize wording and styles.
