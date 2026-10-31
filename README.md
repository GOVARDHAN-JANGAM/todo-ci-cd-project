# TaskFlow - CI/CD To-Do Application

A beginner-friendly To-Do List web application built to demonstrate a real CI/CD workflow using GitHub Actions.

## Technologies
- HTML5
- CSS3
- JavaScript
- GitHub Actions
- GitHub Pages

## Project Structure
```
.
├── index.html
├── style.css
├── script.js
├── README.md
└── .github/workflows/
    └── ci-cd.yml
```

## Run Locally
Clone the repository and open `index.html` in a browser.

## CI/CD Pipeline
The workflow runs on pushes and pull requests to `main`.

### Continuous Integration
1. Checks out the latest source code.
2. Validates that required application files exist.
3. Performs basic HTML checks.

### Continuous Deployment
For successful pushes to `main`, the workflow uploads the website and deploys it to GitHub Pages.

## Testing the Pipeline
Make a small change, then run:

```bash
git add .
git commit -m "Update application"
git push origin main
```

Open the **Actions** tab in GitHub to verify the workflow. After deployment, open the GitHub Pages URL configured in the repository settings.


## Deployment
This project uses GitHub Actions to validate and deploy the site automatically after successful changes to the main branch.
