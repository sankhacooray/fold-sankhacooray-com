# fold.sankhacooray.com

Single-file site (`index.html`, CSS inline) on GitHub Pages from `main`: commit and `git push` to deploy. See README.md.

## Lighthouse
<!-- lighthouse-optimized: 2026-10-31 -->
- Baseline mobile: performance 76, accessibility 96, best-practices 100, SEO 100 (desktop perf 100).
- Fixed: non-blocking Google Fonts + fonts.gstatic.com preconnect; `--text-muted` raised to 4.5:1+ (light #6f6352, dark #958877) and dark `--gold` to #ca7242 (tag chips 4.8:1); project thumbs served as WebP with 480w/800w `srcset` and width/height (JPGs kept as sources).
- Left: cache TTL (GitHub Pages fixes it at 10 min); shared scripts / gtag handled centrally.
