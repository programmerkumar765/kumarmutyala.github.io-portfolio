# Tarun Bheema — AI/ML Engineer Portfolio

Static GitHub Pages portfolio.

## Edit your links
Open `script.js` and replace:

```js
const PORTFOLIO={
  githubUsername:"YOUR_GITHUB_USERNAME",
  linkedinUrl:"https://www.linkedin.com/in/YOUR_LINKEDIN_USERNAME/",
  email:"YOUR_EMAIL@example.com"
};
```

## Recommended GitHub Pages repo
Use `YOUR_GITHUB_USERNAME.github.io` as the repository name.

```bash
cd ~/Desktop/tarun-ai-portfolio
git init
git branch -M main
git add .
git commit -m "Launch AI/ML engineering portfolio"

gh auth status
gh auth switch --user YOUR_GITHUB_USERNAME

gh repo create YOUR_GITHUB_USERNAME.github.io \
  --public \
  --description "AI/ML Engineer portfolio — agentic AI, machine learning, cloud systems, and security research." \
  --source=. \
  --remote=origin \
  --push
```

If Pages is not automatically enabled: Repository → Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

## Accuracy note
AgentOps is labeled as a prototype. Economic Regime Discovery is labeled complete. Research is labeled academic research rather than production implementation.
