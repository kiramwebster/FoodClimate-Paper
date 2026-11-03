# Food Climate Research — Validation Workbench (v14)

An interactive, high-efficiency scientific validation workbench designed for evaluating LLM-extracted climate-hazard and food-species interaction claims across published academic literature.

## 🚀 Live Web Application (GitHub Pages)

- **v14 Validation Workbench:** [https://kiramwebster.github.io/FoodClimate-Paper/](https://kiramwebster.github.io/FoodClimate-Paper/)

---

## 🌟 Key Features

1. **Ultra-Compact Single-Monitor Audit Layout**:
   - Engineered for fast, ergonomic reviewing with zero wasted screen space.
   - One-click Checklist Evaluation: green check (`✓`) or red cross (`✗`) for URL, Hazard, Species, Quote, Summary, Impact Direction, Source Type, and Evidence Type.
   - Contextual note boxes appear automatically only when a discrepancy (`✗`) is flagged.

2. **One-Click Auto-Split Screen Companion Window**:
   - Clicking **`[⧉ Open in 2nd window]`** automatically tiles the Workbench to the left 34% of the screen and snaps the publisher article window to the right 66%.
   - Full hands-free review without manual window dragging or resizing.
   - Quiet synchronization: moving through entries updates the companion window in place without stealing keyboard focus.

3. **Multi-Reviewer Support & Local Persistence**:
   - Review progress is stored safely in `localStorage` in the browser—no database required.
   - Built-in team reviewer profiles and dynamic validation leaderboard.
   - Instant export of reviewed results to CSV format.

4. **v14 Team Pilot Sample**:
   - Balanced 30-entry sample representing all 14 climate hazards (CO2, Drought, Fires, Floods, Heatwaves, Natural Cover Change, Ocean Acidification, Ocean Circulation, Ocean Deoxygenation, Ozone, Precipitation, Sea Level Rise, Storms, and Warming).
   - All entries are 1-of-1 unique papers with verified peer-reviewed sources.
   - Available as an interactive web page and as an Excel spreadsheet in [`v14SAMPLE/v14_pilot_sample_30.xlsx`](v14SAMPLE/v14_pilot_sample_30.xlsx).

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
