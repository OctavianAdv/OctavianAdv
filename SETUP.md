# ⚙️ SETUP GUIDE — Automated GitHub Profile

This guide explains how to activate all the automated workflows for your elite GitHub profile.

---

## 📋 Prerequisites

1. This repo **must** be named exactly `OctavianAdv` (same as your GitHub username)
2. The repo **must** be public

---

## 🐍 1. Snake Animation (Automatic)

**File:** `.github/workflows/snake.yml`

**What it does:** Generates an animated snake eating your contribution graph.

**Setup:** Nothing extra needed! It uses `GITHUB_TOKEN` which is automatically provided.

**Trigger:** Runs every 12 hours + on every push to `main`/`master`.

**Manual trigger:** Go to `Actions` tab → `Generate Snake Animation` → `Run workflow`

> After first run, the snake SVGs will appear in the `output` branch and display on your README.

---

## 📊 2. Advanced Metrics (Requires Token)

**File:** `.github/workflows/metrics.yml`

**What it does:** Generates detailed stats: overview, language breakdown, coding habits, achievements, and isometric calendar.

### Setup:
1. Go to [GitHub Settings → Developer Settings → Personal Access Tokens → Fine-grained tokens](https://github.com/settings/tokens?type=beta)
2. Click **"Generate new token"**
3. Name it `METRICS_TOKEN`
4. Set expiration (recommended: 90 days or no expiration)
5. Under **Repository permissions**, grant:
   - `Contents`: Read-only
   - `Metadata`: Read-only
6. Under **Account permissions**, grant:
   - `Profile`: Read-only  
7. Click **Generate token** and copy it
8. Go to your profile repo → **Settings** → **Secrets and variables** → **Actions**
9. Click **New repository secret**
10. Name: `METRICS_TOKEN`, Value: (paste your token)

**Trigger:** Runs daily at midnight + on push.

**Manual trigger:** Go to `Actions` tab → `Generate GitHub Metrics` → `Run workflow`

---

## ⏱️ 3. WakaTime Coding Stats (Optional but cool)

**File:** `.github/workflows/waka-stats.yml`

**What it does:** Auto-updates your README with real coding time stats (which languages, what time you code, how many hours, etc.)

### Setup:
1. Install [WakaTime](https://wakatime.com/) and create an account
2. Install the WakaTime extension in VS Code (or your editor)
3. Get your API key from [WakaTime Settings](https://wakatime.com/settings/api-key)
4. Go to your profile repo → **Settings** → **Secrets and variables** → **Actions**
5. Click **New repository secret**
6. Name: `WAKATIME_API_KEY`, Value: (paste your WakaTime API key)

**Trigger:** Runs daily at midnight.

> The section between `<!--START_SECTION:waka-->` and `<!--END_SECTION:waka-->` in your README will be auto-replaced with real data.

---

## 🚀 Quick Start (after pushing)

```bash
# 1. Push everything to GitHub
git add -A
git commit -m "🚀 Elite profile setup"
git push origin main

# 2. Go to your repo's Actions tab
# 3. Manually run each workflow once:
#    - Generate Snake Animation
#    - Generate GitHub Metrics  (needs METRICS_TOKEN secret first)
#    - WakaTime Stats           (needs WAKATIME_API_KEY secret first)

# 4. Wait ~2 minutes for workflows to finish
# 5. Refresh your profile page — everything should be live!
```

---

## 🔑 Summary of Required Secrets

| Secret Name | Required? | Where to get it |
|---|---|---|
| `GITHUB_TOKEN` | Auto-provided | Built into GitHub Actions |
| `METRICS_TOKEN` | Yes (for metrics) | [GitHub Personal Access Tokens](https://github.com/settings/tokens?type=beta) |
| `WAKATIME_API_KEY` | Optional | [WakaTime Settings](https://wakatime.com/settings/api-key) |

---

## ❓ Troubleshooting

- **Snake not showing?** → Check the `Actions` tab for errors. Make sure the workflow ran and the `output` branch was created.
- **Metrics empty?** → Ensure `METRICS_TOKEN` is set correctly in repo secrets.
- **WakaTime says "Waiting for data"?** → Install the WakaTime editor extension. Data takes ~24 hours to appear after first install.
- **Images broken?** → Workflows may not have run yet. Trigger them manually from the Actions tab.

---

*All workflows auto-run on schedule. Your profile stays fresh without any manual work.* 🔥
