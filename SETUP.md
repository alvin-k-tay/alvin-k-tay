# Publishing the profile README

## 1. Create the profile repository

1. Sign in to GitHub and go to https://github.com/new
2. Repository name: **exactly your GitHub username** (e.g. if your username is `alvinktay`, the repo is `alvinktay`). GitHub shows a banner confirming it is a "special repository".
3. Visibility: **Public** (required for the profile README to display).
4. Tick **Add a README file**, then click **Create repository**.
5. Open `README.md` in the new repo, click the pencil icon, delete the placeholder, and paste the full contents of this folder's `README.md`. Commit to `main`.

Your profile page at `https://github.com/<username>` will show the README immediately.

### Alternative: push from this folder

Run these in PowerShell from this folder, replacing `<username>`:

```powershell
git init -b main
git add README.md
git commit -m "Add profile README"
git remote add origin https://github.com/<username>/<username>.git
git push -u origin main
```

## 2. Profile bio (160 characters max)

Settings → Public profile → Bio:

```
Behavioral scientist | Columbia University | Psychometrics, computational measurement & AI evaluation | Founder of METER & Weftwell
```

(131 characters.) Also fill in **Name**: Alvin K. Tay, PhD · **Company**: Teachers College, Columbia University · **Website**: https://meterresearch.ai · **Social accounts**: LinkedIn URL.

## 3. Pinned repositories (later)

Pin only once each contains real code, documentation, or reproducible materials:

| Repository | Purpose |
| --- | --- |
| `meter-research` | Public research documentation, benchmarks, and reproducibility materials for METER |
| `ai-behavioral-evaluation` | Experimental evaluations of moral reasoning and robustness under social pressure |
| `psychometric-validation` | Reusable examples of measurement invariance, construct validation, and IRT |
| `multiagent-social-dynamics` | Experiments on social influence and collective AI agent behavior |

Proprietary METER and Weftwell source code stays private.

## 4. Keep it restrained

No animated banners, badge walls, or auto-generated GitHub stats. The README is the narrative; the repositories are the evidence.
