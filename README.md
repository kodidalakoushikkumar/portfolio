# DevOps Portfolio

A responsive portfolio starter built with plain HTML, CSS, and JavaScript.

## 1. Run locally

No build tools are required. From this directory run:

```bash
python3 -m http.server 8000
```

Open <http://localhost:8000>.

## 2. Run with Docker

Build and start the container:

```bash
docker build -t devops-portfolio .
docker run --rm -p 8080:80 devops-portfolio
```

Open <http://localhost:8080>.

## 3. Personalize before publishing

- Replace `Koushik` and the introduction if you want different wording.
- Replace `your-email@example.com` with your email.
- Replace the GitHub and LinkedIn placeholder URLs with your actual profiles.
- Update project descriptions and repository links after you build those projects.
- Remove any skills you have not practiced yet.

## 4. Publish with GitHub Pages

1. Create a GitHub repository named `devops-portfolio`.
2. Push these files to the repository's `main` branch.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **GitHub Actions**.
5. The workflow in `.github/workflows/deploy.yml` publishes the site on each push to `main`.

This is a static website; no backend or secrets are required.
