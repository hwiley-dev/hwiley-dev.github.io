# Hunter Wiley Portfolio Site

Static portfolio site for `hunter-wiley.com`, built for GitHub Pages with a lightweight HTML and CSS stack.

## Project Description

This site is a minimalist portfolio for Hunter Wiley's work in accessible music systems, human-centered tools, and technical systems work. The implementation is intentionally static and framework-free so it stays fast, maintainable, and easy to deploy.

## Deployment Instructions

1. Push the contents of this repository to the branch used for GitHub Pages, typically `main`.
2. In GitHub, open the repository settings and enable GitHub Pages for the root of that branch.
3. Confirm that the `CNAME` file remains committed so the custom domain stays attached.
4. After Pages finishes building, verify that `hunter-wiley.com` resolves to the deployed site.

For a quick local preview, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Domain Configuration Notes

- `CNAME` is set to `hunter-wiley.com`.
- The project spec references GitHub Pages with SiteGround DNS pointed at GitHub Pages records.
- If DNS was already updated at SiteGround, the remaining step is Pages enablement on the GitHub repository.

## Accessibility Philosophy

- Semantic HTML drives the page structure.
- The layout is keyboard accessible and includes a skip link plus visible focus states.
- Styling uses high-contrast text and restrained visual complexity.
- The site avoids unnecessary JavaScript to reduce maintenance and improve reliability.

## Maintenance Instructions

- Edit content directly in the HTML files under the root, `about/`, `contact/`, and `projects/`.
- Keep shared visual changes in `styles.css`.
- Replace any placeholder links or summary copy with finalized public URLs and case-study details as content becomes available.
- Keep assets lightweight and store them under `assets/images/` or `assets/icons/`.
