# Earn Your Keep

This folder contains a static, single-page poster supplement for **Earn Your
Keep: How is Social Value of Businesses Communicated?** It hosts quantitative
plots, topic modeling outputs, collocation analysis, a codebook discourse
report, and an embedded RAG method visualization.

## Edit the Page

- Update figure titles and descriptions in `index.html`.
- Put additional plot files in `assets/`.
- The nav logo uses `assets/logo.drawio.png`.
- The top hero visual uses `assets/logo.drawio.png`.
- The RAG method visualization is embedded from `assets/rag_radar_color_fixed.html`
  with an iframe, so visitors stay on the same page.
- The codebook discourse report is embedded from
  `assets/codebook_report_2021-2025.html`.
- Add a new plot by copying an existing `.figure-card`, changing the image path,
  alt text, title, and caption.

```html
<img src="assets/my-plot.png" alt="Short description of the plot">
```

- Keep explanations short enough for phone readers arriving from the poster QR
  code.

## Free Hosting Options

GitHub Pages is the simplest option for this page:

1. Push this folder to a GitHub repository.
2. In the repository, open **Settings > Pages**.
3. Choose deployment from a branch.
4. Select the branch and folder that contain `index.html`.
5. Use the published URL for the poster QR code.

Other free static hosting options also work:

- Netlify: connect the repository or drag and drop this folder as a static site.
- Cloudflare Pages: connect the repository and deploy it as static HTML.
- Vercel: import the repository and deploy the static files.

Official references:

- GitHub Pages: <https://docs.github.com/github/working-with-github-pages/getting-started-with-github-pages>
- Netlify deploys: <https://docs.netlify.com/site-deploys/create-deploys/>
- Cloudflare static HTML: <https://developers.cloudflare.com/pages/framework-guides/deploy-anything/>
- Vercel deployments: <https://vercel.com/docs/deployments/deployment-methods>
