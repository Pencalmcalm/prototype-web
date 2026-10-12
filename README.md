# Website Prototype

A minimal static website with one white page and placeholder text. It uses plain HTML and CSS and requires no installation or build step.

## Project structure

```text
prototype-web/
├── index.html
├── assets/
│   └── css/
│       └── style.css
├── .gitignore
└── README.md
```

## Open locally

Double-click `index.html` to open the page in your browser.

## Upload to GitHub

1. Create an empty GitHub repository.
2. Choose **Add file → Upload files**.
3. Upload the **contents** of `prototype-web`, including the `assets` folder. Keep `index.html` at the repository root instead of inside an extra `prototype-web` folder.
4. Commit the uploaded files.

The `.gitignore` file is optional for browser uploads. Include it when copying the project into a local Git repository. Upload the extracted project files, not the ZIP itself.

## Optional: publish with GitHub Pages

In the repository's **Settings → Pages**, choose **Deploy from a branch**, select your default branch (usually `main`) and **/ (root)**, and save. GitHub will display the website URL when deployment completes. GitHub Pages availability depends on your repository visibility and account plan.

Reference: [GitHub's publishing source guide](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Continue development

- Edit page text and markup in `index.html`.
- Edit appearance in `assets/css/style.css`.
- Add other assets under `assets` when needed.

Relative asset paths allow the page to work locally and under a GitHub Pages repository URL.
