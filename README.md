# The Nuance Scorecard

**A B2B content audit tool by [Nutgraf](https://www.nutgraf.press) · Ritoban Mukherjee**

Score your B2B content across 10 criteria in four dimensions — Claim & Context, Audience Honesty, Sourcing & Specificity, and Ethical Integrity — and find out whether it earns its argument or just makes a clean pitch.

Built as a companion tool to the article *A B2B Copywriter's Guide to Conveying Nuance and Complexity*, published in the [B2B Insights by Nutgraf](https://www.linkedin.com/newsletters/b2b-insights-by-nutgraf-7406985977816281088/) newsletter.

---

## Live Demo

**[→ nutgraf.press/scorecard](https://nutgraf.press/scorecard)** *(update with your deployed URL)*

---

## What It Does

- 10 scored criteria across 4 editorial sections
- Live score updates as you click (no page reload)
- Three verdict tiers with named rationale:
  - **0–14** — The Clean Pitch Problem
  - **15–21** — Conditionally Honest
  - **22–30** — Genuinely Complex
- Surfaces the weakest-scoring criteria as a revision shortlist
- Print to PDF via browser print dialog

---

## File Structure

```
nutgraf-scorecard/
├── index.html          # Main application (single-file, self-contained)
├── assets/
│   └── nutgraf-logo.png
└── README.md
```

No build step. No dependencies. No npm. Just HTML, CSS, and vanilla JS.

---

## Deploying to GitHub Pages

### Option A — New repository

1. Create a new GitHub repo (e.g. `nutgraf-scorecard`)
2. Upload all files maintaining the folder structure above
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**
4. Your tool will be live at `https://yourusername.github.io/nutgraf-scorecard/`

### Option B — Subdirectory of existing site

1. Drop the `nutgraf-scorecard/` folder into your existing repo
2. Access it at `https://yourusername.github.io/your-repo/nutgraf-scorecard/`

### Custom domain (optional)

To serve from `nutgraf.press/scorecard`:
1. In your repo root, add a `CNAME` file containing your domain: `nutgraf.press`
2. In your DNS settings, add a CNAME record pointing to `yourusername.github.io`
3. Enable HTTPS in GitHub Pages settings

---

## Methodology

The scoring framework adapts four principles from Amanda Ripley's **Complicating the Narratives** essay (Solutions Journalism Network, 2018) for B2B content evaluation:

1. **Listen differently** — surface motivations, not stated positions
2. **Go beneath the problem** — engage with structural reasons a problem is hard to solve
3. **Embrace complexity as a feature** — include details that don't fit the narrative
4. **Counter confirmation bias** — ask what in this piece just confirms what readers already believe

Supporting research: Edelman/LinkedIn 2025 B2B Thought Leadership Report, Cognism 2026 B2B Marketing Predictions, EMBL science communication guidelines, The B2B Playbook (Anti-ICP framework).

---

## License & Attribution

Built by Ritoban Mukherjee · [nutgraf.press](https://www.nutgraf.press) · [ritoban@nutgraf.press](mailto:ritoban@nutgraf.press)

Free to use and adapt with attribution. If you use this in a client workshop or agency workflow, a link back to Nutgraf is appreciated but not required.
