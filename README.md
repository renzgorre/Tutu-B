# tutu-B Digital Magazine

The website for **tutu-B**, the official digital magazine of STEM 11-B at De La Salle University Laguna. The name stands for *Transcending Universal Thresholds, Unlocking Breakthroughs*, and the magazine features student-led writing on technology, innovation and research.

**Live site:** [tutu-b.site](https://tutu-b.site)

## Pages

| Page | Contents |
| --- | --- |
| Home (`index.html`) | Landing banner and the list of issues |
| Publications (`pages/publications.html`) | Published issues, starting with Issue No. 1, *Breaking Thresholds: Pioneering Change, Embracing Humanity* |
| Team (`pages/team.html`) | The magazine's team leaders, researchers and editorial staff |

## Tech

A static site in plain HTML, CSS and JavaScript with no build step. It is responsive, with a mobile navigation menu, and is hosted on GitHub Pages under a custom domain (see `CNAME`).

## Running locally

Pages link to each other with root-relative paths, so serve the folder from a local web server rather than opening the files directly:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Project structure

```
index.html          Home page
pages/              Publications and team pages
css/                Shared and per-page styles
js/                 Navigation and scrolling behavior
assets/             Fonts, images and videos
CNAME               Custom domain for GitHub Pages
```
