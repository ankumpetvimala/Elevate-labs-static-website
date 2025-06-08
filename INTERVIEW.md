# Interview Questions and Answers

This document contains answers to potential interview questions related to the GitHub Pages task, showcasing my understanding as a DevOps Intern at Elevate Labs.

## 1. What is GitHub Pages?
**Answer**: GitHub Pages is a free service by GitHub that allows users to host static websites directly from a GitHub repository. It supports HTML, CSS, and JavaScript, making it ideal for portfolios, documentation, or personal projects. For this task, I used it to deploy my portfolio, highlighting my Elevate Labs internship.

## 2. Can you host dynamic apps here?
**Answer**: No, GitHub Pages is limited to static content—HTML, CSS, and client-side JavaScript. It cannot run server-side code like Node.js, Python, or databases. For dynamic apps, platforms like AWS, Heroku, or Vercel are needed. My portfolio is static, perfectly suited for GitHub Pages.

## 3. What are the limits of GitHub Pages?
**Answer**: GitHub Pages has the following limits:
- **Storage**: 1 GB per repository.
- **Bandwidth**: 100 GB per month.
- **File Size**: Individual files cannot exceed 100 MB.
- **Builds**: Soft limit of 10 builds per hour.
- **Purpose**: Designed for static sites, not server-side apps or heavy computation.
These constraints didn’t affect my portfolio, which is lightweight and static.

## 4. How do you update the website?
**Answer**: To update the website, I commit changes to the repository’s `main` branch (e.g., editing `index.html`) and push them to GitHub. GitHub Pages automatically rebuilds and deploys the updated site within minutes. I tested this by tweaking my portfolio’s CSS during development.

## 5. What happens when you delete the repo?
**Answer**: Deleting the repository removes the associated GitHub Pages site entirely. The URL (e.g., `<your-username>.github.io/portfolio-website`) becomes inaccessible, and all hosted content is lost unless backed up. This underscores the importance of version control and backups.

## 6. What is the default file that loads?
**Answer**: The default file is `index.html`. When users visit the GitHub Pages URL, it automatically serves `index.html` from the root or specified folder. My portfolio uses `index.html` as the entry point, ensuring seamless access.

## 7. Can you use a custom domain?
**Answer**: Yes, GitHub Pages supports custom domains. You configure it in the repository’s Pages settings by adding your domain and setting up DNS records (e.g., CNAME or A records). GitHub provides free HTTPS for custom domains, enhancing security. I haven’t used a custom domain here but understand the process.
