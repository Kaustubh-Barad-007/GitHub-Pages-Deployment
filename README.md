# GitHub Pages Deployment Workflow

A beginner-friendly project demonstrating Continuous Integration and Continuous Deployment (CI/CD) using **GitHub Actions** to automatically deploy a static website to **GitHub Pages**.

🔗 **Project Challenge**: https://roadmap.sh/projects/github-actions-deployment-workflow

---

## 🌟 What is this project about?

When you update code on your computer, you usually have to manually upload it to a server. With **CI/CD**, every time you push changes to GitHub, an automated robot (GitHub Actions) builds and deploys your website automatically!

### Key Concepts

- **GitHub Actions**: An automated workflow runner provided by GitHub to execute tasks like testing, building, and deploying code.
- **GitHub Pages**: A free web hosting service provided by GitHub to host static HTML/CSS/JS websites.
- **Path Filtering**: The workflow is configured to trigger **only** when `index.html` is modified.

---

## 🚀 How It Works

1. You make changes to `index.html`.
2. You commit and push those changes to the `main` branch.
3. GitHub Actions notices `index.html` was changed and triggers `.github/workflows/deploy.yml`.
4. The workflow packages the files and deploys them to GitHub Pages.
5. Your live site updates automatically at:
   `https://Kaustubh-Barad-007.github.io/GitHub-Pages-Deployment/`

---

## 🛠️ GitHub Repository Setup (First-Time Only)

To enable automatic deployments on GitHub Pages:

1. Go to your repository on GitHub: `https://github.com/Kaustubh-Barad-007/GitHub-Pages-Deployment`.
2. Click on **Settings** ⚙️ at the top.
3. On the left sidebar, click **Pages**.
4. Under **Build and deployment** -> **Source**, select **GitHub Actions**.

Now, every push to `index.html` on `main` will trigger the live deployment! 🎉

---

## 📂 Project Structure

```text
GitHub-Pages-Deployment/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── index.html
└── README.md
```
