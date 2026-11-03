# Food Climate Research — Validation Workbench

An interactive scientific validation workbench designed for evaluating LLM-extracted climate-hazard and food-species interaction claims across published academic literature.

## Live Web Application (GitHub Pages)

- **Validation Workbench:** [https://kiramwebster.github.io/FoodClimate-Paper/](https://kiramwebster.github.io/FoodClimate-Paper/)

---

## Key Features

1. **Fast, Ergonomic Reviewing**:
   - One-click Checklist Evaluation: green check (`✓`) or red cross (`✗`) for URL, Hazard, Species, Quote, Summary, Impact Direction, Source Type, and Evidence Type.
   - Contextual note boxes appear automatically only when a discrepancy (`✗`) is flagged.

2. **One-Click Auto-Split Screen Companion Window**:
   - Clicking **`[⧉ Open in 2nd window]`** automatically tiles the Workbench to the left 34% of the screen and snaps the publisher article window to the right 66%.
   - Quiet synchronization: moving through entries updates the companion window in place without stealing keyboard focus.

3. **Multi-Reviewer Support & Local Persistence**:
   - Review progress is stored safely in `localStorage` in the browser—no database required.
   - Built-in team reviewer profiles and dynamic validation leaderboard.
   
---

## 🧩 Optional Chrome Extension (Workbench Sync Assistant)

For complete hands-free window management across all academic publishers (Wiley, Springer, ScienceDirect, etc.), reviewers can install the companion Chrome Extension:
1. Download [`WorkbenchSyncExtension.zip`](WorkbenchSyncExtension.zip) from this repository.
2. Unzip the folder on your computer.
3. In Google Chrome, go to `chrome://extensions`.
4. Turn on **Developer mode** in the top right.
5. Click **Load unpacked** and select the unzipped extension folder.

---

## 📊 Repository Structure

- `index.html`: Main Validation Workbench application pre-loaded with the v14 team test sample.
- `v14SAMPLE/`: Pilot sample files in Excel (`.xlsx`), CSV (`.csv`), and JSON (`.json`) formats.
- `WorkbenchSyncExtension.zip`: Companion Chrome extension for automated split-screen tiling and publisher synchronization.
