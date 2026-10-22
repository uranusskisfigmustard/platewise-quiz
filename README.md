# Platewise — Barbell Loading Quiz

A single-page website for practicing barbell plate loading in **pounds**.

## How it works

- The bar weighs **45 lb**.
- The player loads **only one side**; the opposite side is assumed to match.
- Total barbell weight = **45 + 2 × (sum of selected plates)**.
- Available plates: **45, 35, 25, 10, 5, 2.5, and 1.25 lb**.
- Target generation: approximately **95%** targets using standard plates, **4%** targets requiring 2.5 lb plates, and **1%** targets requiring 1.25 lb plates. Actual frequencies vary randomly.
- Three difficulty ranges: Light, Standard, and Heavy.
- Any valid plate combination that matches the target is accepted.
- Optional running total, answer reveal, solved count, streak, and locally saved best streak.

## Run it locally

Open `index.html` in any modern browser. No server, installation, or dependencies are required.

## Publish with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. In **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select branch **main** and folder **/ (root)**, then click **Save**.
4. The site will be available at `https://uranusskisfigmustard.github.io/platewise-quiz/` after GitHub finishes publishing.

No account registration, analytics, third-party assets, or backend are required.
