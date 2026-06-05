# VkusVill Bonus Bag Portfolio Case Study

Standalone English portfolio landing page for the VkusVill reusable bag / Bonus Bag sustainability project.

The page reframes the original campaign as a sustainability case study: it explains the customer problem, the reusable-bag and QR-code bonus mechanics, user incentives, impact and business value, my role, and skills demonstrated.

## Project files

- `index.html` — single-page portfolio case study, ready to serve from the repository root.
- `styles.css` — responsive visual design and layout styles.

## Preview locally

Because this is a static HTML/CSS page, you can open `index.html` directly in a browser. For a closer GitHub Pages-style preview, run a local static server from the repository root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Deploy with GitHub Pages

This repository is prepared for GitHub Pages because `index.html` is located at the repository root and uses a relative stylesheet path.

Exact setup instructions:

1. Push this repository to GitHub at `can-did/reusablebag`.
2. Open the repository on GitHub.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the branch you want to publish, usually `main` or `work`.
6. Select the root folder `/`.
7. Click **Save**.
8. After GitHub finishes deployment, the public page will be available at:

```text
https://can-did.github.io/reusablebag/
```

If you publish from a non-default branch, GitHub Pages may take a few minutes to build after each push.
