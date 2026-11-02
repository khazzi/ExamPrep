# ICAN Taxation 2026 Chapter Quizzes

This is a static website. It has no build step, server-side runtime, or package dependencies.

## Deploy to Vercel

### Connect GitHub

1. Import `khazzi/ExamPrep` into Vercel and authorize the GitHub connection if prompted.
2. Keep **Root Directory** set to `.` (the repository root).
3. Use the **Other** framework preset. Leave the build command empty; the site is served directly from `index.html`.
4. Deploy. Vercel will build and deploy future pushes automatically.

### Deploy with the Vercel CLI

From this directory, run `vercel` to create a preview deployment, then `vercel --prod` to deploy to production. The Vercel CLI must be installed and authenticated first.

The quiz itself runs in the browser. Google Fonts are loaded from Google Fonts when available; the page has system-font fallbacks.

The layout adapts to narrow screens: chapter navigation becomes a horizontally scrollable, snap-aligned list, quiz controls remain touch-friendly, and selecting a chapter brings it into view.
