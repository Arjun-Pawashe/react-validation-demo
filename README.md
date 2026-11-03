# React Client-Side Validation Application

This is an individual React project demonstrating form validation, state management, interactive user feedback, and deployment to GitHub Pages.

## Project Setup & Usage

1. Extract the zip file and navigate into the folder:
   ```bash
   cd react-validation-demo
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the application locally:
   ```bash
   npm start
   ```

## Deploying to GitHub Pages

1. In `package.json`, update `"homepage"` to match your GitHub details:
   `"homepage": "https://<your-github-username>.github.io/<your-repo-name>"`
2. Initialize Git, commit, and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-github-username>/<your-repo-name>.git
   git push -u origin main
   ```
3. Run deploy command:
   ```bash
   npm run deploy
   ```
