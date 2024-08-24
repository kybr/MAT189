```HTML  
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/p5.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/addons/p5.sound.min.js"></script>
  </head>
  <body>
    <script src="sketch.js"></script>
    <p>
      This is Larry Keeks.
    </p>
  </body>
</html>
```

Add the `<meta>` and `<script>` tags from the code above to your `index.html` of your GitHub pages repository.


```js
function setup() {
  createCanvas(windowWidth, windowHeight);
  pixelDensity(1);
}

let n = 0;
function draw() {
  clear();
  fill(n);
  noStroke();
  circle(width / 2, height / 2, 50);
  n += 2.1;
  if (n >= 255) {
    n -= 255;
  }
}
```

Add the code above to a net file (`sketch.js`) in your GitHub Pages repository.

The code may also be found here:

<https://editor.p5js.org/kybr/sketches/lsPfBtEGIH>

Go to this link and "duplicate" the code to start your own sketch. In the editor, choose File > Duplicate.



- Browse to your GitHub Pages repository. Mine is <https://github.com/kybr/kybr.github.io>
- Add a new file, `sketch.js` and file it with this code:
  ```js
  function setup() {
    createCanvas(windowWidth, windowHeight);
    pixelDensity(1);
  }
  
  let n = 0;
  function draw() {
    clear();
    fill(n);
    noStroke();
    circle(width / 2, height / 2, 50);
    n += 2.1;
    if (n >= 255) {
      n -= 255;
    }
  }
  ```
  - Save/commit
- Edit `index.html`; Add `<script>` and `<meta>` tags to your HTML like this has:
  ```html
  <!DOCTYPE html>
  <html>
    <head>
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/p5.js"></script>
      <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/addons/p5.sound.min.js"></script>
    </head>
    <body>
      <script src="sketch.js"></script>
    </body>
  </html>
  ```
  - Save/commit
- Browse to your GitHub Pages site and refresh
