# GitHub Actions – Automated Website Deployment

## 📌 About the Project

This project demonstrates how to automate website deployment using **GitHub Actions** and **GitHub Pages**.

Whenever changes are made to the `index.html` file and pushed to the `main` branch, GitHub Actions automatically runs the deployment workflow and updates the website.

The main goal of this project is to understand the basics of CI/CD (Continuous Integration and Continuous Deployment).

## 🛠️ Technologies Used

- HTML5
- Git and GitHub
- GitHub Actions
- YAML
- GitHub Pages
- Ubuntu (GitHub-hosted runner)

## ⚙️ How It Works

1. Create or update the `index.html` file.
2. Push the changes to the GitHub repository.
3. GitHub Actions automatically detects the changes.
4. The workflow starts running on an Ubuntu runner.
5. The website files are prepared and uploaded as a deployment artifact.
6. GitHub Pages deploys the updated website.

## 📂 Project Structure

```text
gh-deployment-workflow/
│
├── .github/
│   └── workflows/
│       └── deploy.yml
│
├── index.html
│
└── README.md
```

## 🚀 Deployment

This project uses GitHub Pages for hosting and GitHub Actions for automated deployment.

To view the deployed website:

1. Open the GitHub repository.
2. Go to **Settings → Pages**.
3. Find the published website URL.
4. Open the URL in your browser.

## 🎯 What I Learned

- Basics of CI/CD pipelines.
- Creating automated workflows using GitHub Actions.
- Writing workflow configuration files using YAML.
- Using GitHub-hosted Ubuntu runners.
- Automating website deployment with GitHub Pages.
- Understanding how code changes can trigger automated deployments.

## 👨‍💻 Author

**Pratham**

GitHub: [@prathamp16](https://github.com/prathamp16)

---

⭐ If you find this project useful, feel free to explore the repository!
