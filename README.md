# EngineeringAI Lab GitHub Pages

This repository hosts the static GitHub Pages website for EngineeringAI Lab. The
site does not require a build step; GitHub Pages can publish it directly from the
repository root.

## Site Structure

- `index.html`: About page with Who We Are, We Work On, Highlights, News, and Latest Posts
- `team.html`: leaders, current members, and alumni
- `projects.html`: research directions and representative systems
- `publications.html`: selected team papers and manuscripts
- `advisors.html`: collaborating advisors and partners
- `news.html`: lab updates
- `styles.css`: shared styling for all pages

## Recommended Repository Name

For an organization homepage, name the repository:

```text
EngineeringAI-LAB.github.io
```

The default published URL will be:

```text
https://engineeringai-lab.github.io/
```

If you use a regular project repository name, such as `EngineeringAI-LAB`, the
published URL will include the repository path:

```text
https://engineeringai-lab.github.io/EngineeringAI-LAB/
```

## Deployment

1. Create a repository named `EngineeringAI-LAB.github.io` under the `EngineeringAI-LAB` organization.
2. Initialize this directory as a git repository and push it to that remote.
3. Open `Settings -> Pages`, choose `Deploy from a branch`, select the `main` branch, and choose `/root`.
4. Wait for GitHub Pages to finish deployment.

Useful commands:

```bash
git init -b main
git add .
git commit -m "Initial GitHub Pages site"
git remote add origin git@github.com:EngineeringAI-LAB/EngineeringAI-LAB.github.io.git
git push -u origin main
```

If you prefer an HTTPS remote:

```bash
git remote add origin https://github.com/EngineeringAI-LAB/EngineeringAI-LAB.github.io.git
git push -u origin main
```
