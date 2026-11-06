# mansoor-mamnoon.github.io

Personal site for Mansoor Mamnoon. Live at https://mansoor-mamnoon.github.io/.

Plain HTML and one stylesheet. No framework, no build step, no JavaScript apart from Google Analytics. Fonts are the system's own, and dark mode follows the operating system setting.

| File | What's on it |
|---|---|
| `index.html` | Short intro, projects, work, link to notes |
| `projects.html` | One section per project (`#vxlantracer`, `#llmfirewall`, `#orderbook`, `#offlinerl`, `#edgedeployer`) |
| `experience.html` | Work, teaching, education, awards |
| `resume.html` | HTML resume that also prints cleanly; the PDF is in `assets/` |
| `about.html` | Background |
| `notes.html` | Short technical notes |
| `style.css` | All styling |
| `llms.txt`, `sitemap.xml`, `robots.txt` | For crawlers |

To preview locally:

```
python3 -m http.server 8000
```

then open http://localhost:8000. The site deploys when you push to GitHub Pages.
