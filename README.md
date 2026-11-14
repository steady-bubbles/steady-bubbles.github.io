# steady-bubbles.github.io

The website [steady-bubbles.github.io](https://steady-bubbles.github.io): a menu of projects on
steady bubbles in an inviscid stream, and the published pages of these projects.

This repository only hosts what the website shows. Each project's code, simulations, data and the
source of its page live in the project's own repository; its built page is copied here into a
folder of the same name.

| folder | page | source |
|---|---|---|
| `axisymmetric/` | [steady-bubbles.github.io/axisymmetric](https://steady-bubbles.github.io/axisymmetric/) | [steady-bubbles/axisymmetric](https://github.com/steady-bubbles/axisymmetric) |
| | Spiraling (coming soon) | |

To add a project: put its built page in a new folder (`<name>/index.html`), add a line to the
list in `index.html` and to the table above. Every project page links back to the menu with the
absolute address `https://steady-bubbles.github.io/`, so the link also works from a local copy.
The empty file `.nojekyll` must stay: it makes GitHub Pages serve the files as they are.
