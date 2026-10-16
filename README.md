# Sonam Barnala — Portfolio

Personal site for Sonam Barnala, backend and distributed systems engineer (Java, Spring Boot, Kafka, Go, Raft, React).

Single static page, no build step: `index.html`.

## Publish on GitHub Pages

1. Create a public repo named `Sonam1999.github.io`.
2. Upload `index.html` and this `README.md` to the repo root (or `git push`).
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. The site goes live at `https://Sonam1999.github.io` within a minute or two.

## Add your links

At the bottom of `index.html`, fill in the `LINKS` object. Empty links stay hidden.

```js
const LINKS = {
  linkedin: "https://www.linkedin.com/in/your-handle",
  github: "https://github.com/your-username",
  resume: "resume.pdf"   // upload your resume PDF to the repo root
};
```
