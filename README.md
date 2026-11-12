# bossy-ye.github.io

Personal academic website of Boshuai Ye — doctoral researcher in quantum software
engineering at the M3S Research Unit, University of Oulu.

Live at [bossy-ye.github.io](https://bossy-ye.github.io/).

Plain HTML and CSS, no build step and no JavaScript. The layout follows the
academicpages convention: a left sidebar with contact links, an "About me" home
page, and a publications page grouped by research topic.

Pages: `index.html`, `publications.html`, `cv.html`. The sidebar is repeated in
each page, so edit all three when it changes. `about.html`, `contact.html`,
`projects.html`, `research.html` and `teaching.html` are redirects that keep older
links working.

Icons come from Font Awesome on cdnjs; every link also has a text label, so the
pages still work if the icons fail to load.

To add a portrait, save a square photo as `assets/portrait.jpg` and uncomment the
`<img class="avatar">` line in each page's sidebar.

The downloadable CV is `assets/boshuai-ye-cv.pdf`; replace that file to update it.

A GitHub Actions workflow checks every link on push, on pull requests and weekly.
Hosts that reject automated requests are listed in `.lycheeignore`.
