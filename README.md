# GMAT Focus Mock

An offline practice simulator for the GMAT Focus Edition. It is one HTML file with no build step, no server, no API and no account. All progress is stored in the browser.

## Run locally

Open `index.html` in any modern browser. Nothing needs to be installed.

## What it does

- **Section order.** Choose one of six orders of Quantitative Reasoning, Verbal Reasoning and Data Insights.
- **Rules.** *Strict simulation* follows the real exam: fixed section timers, no going back into a finished section, and a limited number of answer edits. *Practice* relaxes these.
- **Timing.** Each section has a timer. A section that runs out is submitted automatically.
- **Transitions.** Short break and transition screens sit between sections. Completed sections are locked.
- **Instructions screen.** Shown before the first section.
- **Leave-page warning.** The browser warns before you close or reload during an active sitting. A reload resumes the sitting where it stopped.
- **Full screen.** A toolbar button toggles full-screen mode when the browser allows it.
- **Calculator.** Available in Data Insights only, as on the real exam.
- **Review Center and results.** Question grid, mark-for-review, review of every item, and a results dashboard with section analytics.
- **Test library.** Several full mock tests are built in. Each one shows its source and keys.

## Deploy

The app is static, so any static host works.

**GitHub Pages**
1. Open the repository settings, then *Pages*.
2. Under *Build and deployment*, set *Source* to *Deploy from a branch*.
3. Choose branch `main` and folder `/ (root)`, then save.
4. The site is published at `https://krish-5.github.io/gmat-mock/`.

**Netlify or Vercel**
Drag the folder in, or connect the repository. No build command is needed and the publish directory is the repository root.

## Notes on content

- Question text and answer keys were transcribed from screenshots of third-party practice material and solved independently. Some keys are marked medium or low confidence inside the app. The authors of the source material hold any rights to their questions. Check those rights before publishing the test content publicly.
- Results and progress live only in the browser that ran the sitting (localStorage). Clearing site data erases them.
- This is not affiliated with GMAC or the GMAT. GMAT is a registered trademark of GMAC.

