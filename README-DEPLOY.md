# Hemalatha portfolio — latest Vercel deployment package

Prepared from the latest local portfolio on 24 October 2026.

## Included
- Latest premium portfolio with light/dark themes and opening name animation.
- Seven interactive picture panels and the expanded library of 16 illustrations.
- Education roadmap, six expandable tool cards, Tamil/English language interaction,
  learning map, three report-cover previews, and portrait contact card.
- Corporate Tax Strategy (70 pages), NIFTY 50 research (81 pages),
  and grievance-handling research (78 pages), with previews and downloads.
- Original resume, six certificates, and theme comparison page.

## Deploy on Vercel
1. Extract this ZIP.
2. Put `vercel.json`, `public/`, and this README into the root of a Git repository.
3. In Vercel, choose Add New > Project and import that repository.
4. Select Framework Preset: Other. Use the repository root as Root Directory.
5. The included vercel.json sets Output Directory to `public`, with no build or
   install command. No environment variables are needed.
6. Click Deploy.

Upload the extracted files to the repository, not the ZIP itself.
The main page is `/`; the side-by-side theme comparison is `/compare.html`.

Official configuration guide:
https://vercel.com/docs/builds/configure-a-build

## Important behavior
The contact form prepares an email draft in the visitor's email application;
the visitor reviews and sends it. This package has no email server or database.
PDF pop-ups show the original first page. Open PDF and Download PDF provide the
complete document. Theme preferences are remembered in the visitor's browser.

## Hosting-specific metadata
The old ChatGPT Sites canonical URL, structured-data URL, and absolute social
image URL were removed from this export so it does not point search engines at
the previous host. After choosing your permanent Vercel/custom domain, you can
add its canonical URL and an absolute Open Graph image URL to public/index.html.
The website works without these optional metadata values.

## Local preview
From this extracted folder, run: python -m http.server 8765 --directory public
Then open http://localhost:8765

This archive is ready for deployment; creating it does not publish to Vercel.
