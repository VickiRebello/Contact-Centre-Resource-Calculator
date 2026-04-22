# Headcount Planner — Call Centre Resource Calculator

## Deploy to GitHub Pages (2 steps)

### 1. Create a GitHub repo
Go to https://github.com/new and create a repo named **callcentre-planner** (public).

### 2. Run these commands in this folder

Replace `YOUR_USERNAME` with your GitHub username:

```bash
npm install
git init
git remote add origin https://github.com/YOUR_USERNAME/callcentre-planner.git
git add .
git commit -m "initial commit"
git push -u origin main
npm run deploy
```

Then go to: **GitHub repo → Settings → Pages → Source → gh-pages branch → Save**

Your app will be live at: **https://YOUR_USERNAME.github.io/callcentre-planner/**

## Updating the app
After any changes, just run: `npm run deploy`

## Run locally
```bash
npm install
npm run dev
```
