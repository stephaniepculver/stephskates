# Steph Skates — Website

Static GitHub Pages site for [stephskates.com](https://stephskates.com).

## Setup

### Enable GitHub Pages
1. Go to repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / root `/`
4. Save — site publishes in ~60 seconds

### Connect Custom Domain
1. In **Settings → Pages → Custom domain**: enter `stephskates.com`
2. Save — GitHub will verify DNS and enable HTTPS

### DNS (Namecheap)
Point `stephskates.com` to GitHub Pages with these A records:

| Type | Host | Value |
|------|------|-------|
| A    | @    | 185.199.108.153 |
| A    | @    | 185.199.109.153 |
| A    | @    | 185.199.110.153 |
| A    | @    | 185.199.111.153 |
| CNAME | www | stephaniepculver.github.io |

DNS propagation takes up to 48 hours. HTTPS activates automatically once DNS resolves.

### Contact Form
The form in `index.html` uses Formspree. To activate:
1. Create a free account at [formspree.io](https://formspree.io)
2. Create a new form
3. Replace `YOUR_FORM_ID` in `index.html` with your form endpoint ID

## Fonts
Loaded from Google Fonts (no installation needed):
- **Bebas Neue** — wordmark
- **Cormorant Garamond** Bold 700 + SemiBold Italic 600i — display/headlines
- **DM Sans** Light 300, Regular 400, Medium 500, SemiBold 600 — body/UI

## Brand Colors
| Name | Hex |
|------|-----|
| Pearl White | `#F5F6F7` |
| Lagoon Blue | `#6D93A7` |
| Deep Graphite | `#31363D` |
| Blue Slate | `#7D8FA3` |
| Mist Gray | `#D2D8DD` |
| Brushed Platinum | `#BFC5C9` |
