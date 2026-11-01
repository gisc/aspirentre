# aspirentre — client-side simulation

A static, client-side-only simulation of the structure of an invention-learning
platform: a homepage with a gallery and campus map, an inspiration hall, an
online course route, a mock competition review room, and a future observatory.

This is an original simulation built from the observed public structure. It
contains no backend, no accounts, no real AI mentors, and no locked lesson
content. All data shown (gallery items, scores, clocks, trend indices) is
generated or mocked in the browser.

## Pages

- `index.html` — homepage, gallery carousel, campus map
- `inspiration/index.html` — prompt a problem, get suggestion chips and a
  simulated mentor discussion (all client-side templates)
- `course/index.html` — course route: Season 1 chapters 1–12, plus the
  planned chapters 13–40 route
- `icc/index.html` — mock review room with an entry form that does not submit
  anywhere
- `future/index.html` — observatory dashboard with live clocks, trend bars,
  signal filters and a course map

## GitHub Pages

Publish the `main` branch root as a GitHub Pages site. The expected URL is:

https://gisc.github.io/aspirentre/

If Pages is not yet enabled, enable it in the repository Settings → Pages,
deploying from the `main` branch root, then wait for the first deployment.
