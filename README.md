# complexity.blog

A minimal technical blog built with plain HTML/CSS. No build step, no framework, no dependencies.

## Setup on GitHub Pages

1. Create a repo named `your-username.github.io` (or any repo name)
2. Push this folder to the `main` branch
3. Go to **Settings → Pages → Source** → select `main` branch, root `/`
4. Your site will be live at `https://your-username.github.io`

## Structure

```
├── index.html              ← Homepage (posts + projects)
├── posts/
│   └── hierarchical-rl-mpc.html  ← Sample post
├── projects/               ← Project detail pages (add as needed)
├── assets/
│   ├── css/
│   │   └── style.css       ← All styles
│   ├── js/                 ← Scripts (if needed later)
│   └── img/                ← Images
└── README.md
```

## Adding a New Post

1. Copy `posts/hierarchical-rl-mpc.html` as a template
2. Update the title, date, tags, and prose content
3. Add a new `<a class="post-card">` entry to `index.html`

## Customization

All design tokens live in `:root` variables in `style.css`:
- `--accent` — change the green to whatever suits you
- `--bg` / `--bg-card` — background shades
- Fonts are loaded from Google Fonts (Instrument Serif, DM Sans, JetBrains Mono)

## License

Content is yours. Code is MIT.
