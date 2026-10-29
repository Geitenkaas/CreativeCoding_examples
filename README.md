# Creative Coding Sketches

Eleven short p5.js sketches for the creative coding lesson, one folder each:

| # | Sketch | Idea |
|---|--------|------|
| 01 | Variables and conditionals | A variable holds a value; `if` picks a branch each frame |
| 02 | Loops | A nested loop visits every cell of a grid |
| 03 | Functions | Name a step so you can reuse it, or return a value |
| 04 | Objects | A class bundles data with behaviour |
| 05 | Nearest point search | A linear search keeps the best so far |
| 06 | Mapping and easing | `map()` rescales, `lerp()` eases |
| 07 | Pixels as an array | Four numbers per pixel: red, green, blue, alpha |
| 08 | Vectors and transforms | Direction and length; moving the drawing space |
| 09 | 3D with WEBGL | A third axis and a camera (drag to orbit) |
| 10 | A signal over time | Keep a history of samples and smooth it |
| 11 | Particle system | Many simple objects plus forces (hold the mouse down) |

## Get it running

1. On GitHub, click **Code → Download ZIP** and unzip it (or `git clone` the repo).
2. In VS Code, choose **File → Open Folder…** and pick the unzipped folder.
3. Install the **Live Server** extension if you don't have it. VS Code will offer it,
   because this folder recommends it.
4. Right-click `index.html` and choose **Open with Live Server**. A menu of all the
   sketches opens in your browser.
5. Click a sketch. To change it, open that sketch's `sketch.js` in VS Code, edit it and
   save. The browser reloads with your change.

No Live Server? Double-clicking any `index.html` also works, but you'll have to refresh
the browser yourself after each save.

## What's in each folder

```
sketches/01-variables-and-conditionals/
  index.html   the page: loads p5.js, then sketch.js
  sketch.js    the code - this is the file to edit
```

`style.css` at the top level styles every page. To start your own sketch, copy any sketch
folder, rename it, and add a link to it in the top-level `index.html`.

If a sketch shows a blank page, open the browser's developer console (F12) to see the error.

p5.js 1.9.4 loads from cdnjs, so you need an internet connection. Reference:
https://p5js.org/reference/
