# plstartme — Community Link Hub

A beautiful, single-file community link hub. Inspired by [plstart.me](https://plstart.me) — full credit and huge thanks to the original developer.

**Template created by [Frank White (@WhankFrite)](https://x.com/WhankFrite) / [0xWhankFrite on GitHub](https://github.com/0xWhankFrite)**

---

## ✨ Features

- Dark/light mode toggle
- Real-time search across all links
- Scroll-spy category pills
- Copy link with toast notification
- Keyboard shortcuts: `Ctrl+K` to search, `Esc` to clear
- Back-to-top button
- Fully responsive (mobile-first)
- Zero dependencies — single HTML file

## 🚀 Deploy

This is a single `index.html` file. Deploy anywhere:

| Platform | Steps |
|----------|-------|
| **Vercel** | Import this repo at [vercel.com/new](https://vercel.com/new) |
| **Netlify** | Drag the folder to [app.netlify.com/drop](https://app.netlify.com/drop) |
| **GitHub Pages** | Settings → Pages → Deploy from branch `main` |
| **IPFS** | Pin `index.html` via Pinata or Fleek |

## ✏️ Customise in 2 minutes

Open `index.html` and edit the `CONFIG` object at the top of the `<script>` section:

```js
const CONFIG = {
  communityName : "YourCommunity",
  tagline       : "All-in-One Links for YourCommunity",
  logoEmoji     : "🔗",
  githubUrl     : "https://github.com/you/your-repo",
};
```

Then edit the `CATEGORIES` array to add your own links.

## 📄 License

MIT — free to use, fork, and customise for any community.
