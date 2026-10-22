# Carrying the TVS Way

JAIN University's page for TVS Institute for Quality and Leadership.

This is a static site: one `index.html` with all the motion (kolam drawing, scroll lines, map, translator) built into it. No build step and no install.

## Deploy on Vercel

Option A, in the browser:
1. Go to vercel.com/new and sign in.
2. Choose to deploy without Git (or create a new project), and upload this folder.
3. Framework preset: **Other**. Leave build command and output directory empty.
4. Deploy. The animations run as soon as the page loads.

Option B, from a terminal in this folder:

    npx vercel --prod

Accept the defaults; when asked for a framework, choose **Other**.

## Notes

- Fonts load from Google Fonts, so the page needs an internet connection.
- Fully responsive: beautifully visible and optimized across phones, tablets, and laptops.
- To preview locally, run `npx serve .` in this folder and open the address it prints.
