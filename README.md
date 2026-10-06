# CS-573 Optimization Methods (2026)
Material for CS-573 / HY573 Optimization Methods, a graduate course at
the Computer Science Department, University of Crete.

## Interactive demos

`index.html` is a hub page that links to every demo in the `Demos/` folder,
grouped by lecture. Once GitHub Pages is on, it is available at:

https://gtsagkatakis.github.io/CSD573-Optimization-Methods-2026/

### Adding a new demo

There is no code to edit and no list to update. Just upload the file:

1. Open the `Demos` folder on GitHub.
2. Click **Add file → Upload files**, drop in the `.html` file and commit.

The demo shows up on the hub page by itself, usually within a few minutes.

**Name the file with its lecture number**, for example
`CSD573_Lecture_5_newton_method.html`. The number after `Lecture_` decides
which group the demo goes under. Files without a lecture number go under "Other".

**The button text comes from the demo's `<title>`.** A title like
`CS-573 · Newton's method` shows up as "Newton's method". If the file has
no title, the hub builds a name from the file name instead.

To remove or rename a demo, delete or rename the file in `Demos/`.

### How it works

GitHub Pages cannot list the files in a folder, so each time someone opens the
hub, the page asks GitHub's public API what's in `Demos/` and builds the
buttons from that list. To keep those requests down, each browser saves the
list for 10 minutes. That's why a new upload can take a few minutes to appear.
A hard refresh doesn't clear the saved list. Opening the page in a private
window does.

GitHub allows 60 of these requests per hour from each network address. If a
large class on one shared network ever hits that limit, the hub shows a link to
the `Demos` folder on GitHub instead.

### Turning on GitHub Pages (one time)

Settings → Pages → Source: **Deploy from a branch** → Branch: `main`, folder
`/ (root)` → Save.
