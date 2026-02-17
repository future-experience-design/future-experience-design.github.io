# FED Lab Homepage

Lightweight static website for a research lab. No build step required.

## 1) Local preview

Open `index.html` directly in a browser, or run:

```bash
cd lab-homepage
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## 2) Edit content

- Main page: `index.html`
- Members: `people.html`
- Publications: `publications.html`
- Contact: `contact.html`
- Global style: `styles.css`

## 3) Push to GitHub

```bash
cd lab-homepage
git init
git add .
git commit -m "Initial lab homepage"
git branch -M main
git remote add origin https://github.com/<YOUR_ID>/<REPO_NAME>.git
git push -u origin main
```

## 4) Publish with GitHub Pages

1. Open GitHub repository.
2. Go to `Settings` -> `Pages`.
3. In `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main` and folder `/ (root)`
4. Save and wait 1-3 minutes.
5. Open your published URL:
   - `https://<YOUR_ID>.github.io/<REPO_NAME>/`
