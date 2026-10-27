# Ayesha Binte Mostofa: personal website

Academic homepage of Ayesha Binte Mostofa, PhD student in Computer Science at the University of Massachusetts Amherst (Security Research Group, advised by Dr. Pubali Datta).

Live site: https://ayeshathoi.github.io/

## Contents

| Path | Description |
|---|---|
| `index.html` | Homepage: about, research interests, news, research, publications, experience and education, honors and service, projects, and beyond research |
| `undergrad.html` | Undergraduate projects, with filters and the course page |
| `legacy.html` | Previous homepage, kept but not linked |
| `assets/css/site.css` | Site styles (Inter and Source Serif 4) |
| `assets/img/` | Images, including the profile photo |
| `files/Ayesha_Resume_Internship_2026.pdf` | Current one-page resume |

## Development

The site is static HTML and CSS with no build step. To preview it locally:

```
python3 -m http.server 8000
```

Then open http://localhost:8000. When `assets/css/site.css` changes, update its `?v=` query string in the HTML files so browsers load the new version.

## Resume

The resume is compiled with XeLaTeX. The source requires the Font Awesome fonts `fa-brands-400.ttf` and `fa-solid-900.ttf` in a `fonts/` folder. Copy the compiled PDF to `files/` to update the website link.

## License

See `LICENSE`.
