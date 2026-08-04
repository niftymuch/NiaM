# Nia M. — personal website

A small, static personal site: *living & learning in a naturally beautiful world.*

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Landing page (title, bio, star navigation, animations) |
| `resume.html` / `work.html` / `time.html` | The three star sub-pages |
| `styles.css` | Shared styling + all animations |
| `subpage.css` | Extra styling for the sub-pages |
| `assets/bunny.png` | **Your** mechanical-bunny PNG (see below) |
| `assets/bunny.svg` | Fallback bunny used automatically if the PNG is missing |

## The bunny image

The site loads `assets/bunny.png`. If that file is missing it automatically
falls back to a hand-drawn `assets/bunny.svg` recreation. To use your exact
image, just save it as:

```
assets/bunny.png
```

No code changes needed — refresh the page and it appears.

## Animations

- **Butterfly** (near the title) — flaps its wings and drifts. *Animated.*
- **Bubbles** — rise and drift up the screen. *Animated.*
- **Dragonfly** (over the bio) — *static*, as requested.
- **Bunny** — *static*.

Animations respect `prefers-reduced-motion`.

## Hosting on GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Pick your branch and the `/ (root)` folder, then **Save**.
5. Your site publishes at `https://<username>.github.io/<repo>/`.
