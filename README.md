# gopikagopikrishnan.github.io

Personal academic website of Gopika Gopikrishnan, served by GitHub Pages.

Plain static HTML: no build step and no Jekyll (`.nojekyll` turns it off).

| Path | What it is |
|---|---|
| `index.html` | Homepage: about, news, publications, projects, experience, awards, talks |
| `projects/index.html` | Projects page |
| `gallery/index.html` | Research photo gallery (filters: Conferences, Talks, Lab, Internships) |
| `misc/index.html` | Art and music: watercolour, glass painting, crafts, singing, kalimba |
| `images/` | Project figures and favicons |
| `images/logos/` | Organisation logos for the Experience section |
| `gopika-gopi-krishnan.jpg` | Profile photo |
| `cv.pdf` | CV (upload here; the CV menu link and `/cv/` point to it) |
| `about/`, `publications/`, `talks/`, `cv/`, `lab/` | Redirects that keep old links working |

To edit: change the HTML directly. Colours: teal accent `#5EEAD4`, amber accent `#F2B866`, background `#0A0E13`. Font: Lato.
To add a gallery photo, put it in `images/gallery/` and replace a `[ADD PHOTO]` placeholder tile in `gallery/index.html` with an `<img>`.
To preview locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
