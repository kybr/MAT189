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
