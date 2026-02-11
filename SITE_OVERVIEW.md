# Site Overview

## Technology Stack

| Technology | Purpose |
|---|---|
| [Jekyll](https://jekyllrb.com/) | Static site generator (GitHub Pages default) |
| [Kramdown](https://kramdown.gettalong.org/syntax.html) | Markdown processing engine |
| GitHub Pages | Hosting and automatic builds |
| [Google Fonts](https://fonts.google.com/) | Typography (Scope One, Indie Flower, Share Tech Mono) |
| [jQuery 1.10.2](https://jquery.com/) | JavaScript library (loaded via CDN) |
| [animate.css v3.5.1](https://animate.style/) | CSS entrance animations |

---

## Project Structure

```
rishikhaneja.github.io/
├── _config.yml              # Jekyll configuration
├── _layouts/
│   ├── default.html         # Base HTML template (nav, footer, fonts, scripts)
│   └── post.html            # Blog post template (title, date, content). Extends base.
├── blog/
│   └── index.html           # Blog listing page
├── css/
│   ├── main.css             # All custom styles
│   └── animate.min.css      # animate.css animation library
├── doc/
│   ├── resume.pdf
│   └── resume_old.pdf
├── me/
│   └── index.html           # About / bio page
├── res/
│   └── favicon.ico          # Site favicon
├── index.html               # Home / landing page
```

---

## Jekyll Configuration

- **name** — Site-wide title used in templates
- **markdown** — Kramdown engine for Markdown-to-HTML conversion
- **permalink** — Blog post URLs pattern

---

## Animations

Powered by **animate.css v3.5.1**:

- Navigation bar: `bounceInDown` (drops in from the top)
- Footer: `bounceInUp` (rises from the bottom)

---

## How to Run Locally

1. Install [Ruby](https://www.ruby-lang.org/) and [Jekyll](https://jekyllrb.com/docs/installation/):
   ```
   gem install jekyll bundler
   ```

2. Serve the site:
   ```
   jekyll serve
   ```

3. Open [http://localhost:4000](http://localhost:4000) in a browser.

Since there is no Gemfile, this uses the system-installed Jekyll. Alternatively, push to a GitHub repository named `<username>.github.io` and GitHub Pages will build and serve it automatically.
