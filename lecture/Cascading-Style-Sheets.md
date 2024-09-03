- CSS ~ Cascading Stype Sheets
- HTML ~ HyperText Markup Language



## CSS

Say how HTML tags should look. Specify style rules for tags, ids, and classes.



[Selectors](https://www.w3schools.com/cssref/css_selectors.php):

```css
tag {
  /* rules */
}

#id {
  /* rules */
}

.class {
  /* rules */
}
```


## Flexbox

```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.9.0/p5.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.9.0/addons/p5.sound.min.js"></script>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <!--- <script src="sketch.js"></script> -->

    <div class="container">
      <div class="project" id="project1">1</div>
      <div class="project" id="project2">2</div>
      <div class="project" id="project3">3</div>
      <div class="project" id="project4">4</div>
      <div class="project" id="project5">5</div>
      <div class="project" id="project6">6</div>
    </div>
  </body>
</html>
```

```css
.container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  align-content: flex-start;
}

.project {
  width: 200px;
  height: 200px; 
  font-size: 8em;
  text-align: center;
}
#project1 {
  background-color: hsl(0, 100%, 70%);
}
#project2 {
  background-color: hsl(30, 100%, 70%);
}
#project3 {
  background-color: hsl(60, 100%, 70%);
}
#project4 {
  background-color: hsl(90, 100%, 70%);
}
#project5 {
  background-color: hsl(120, 100%, 70%);
}
#project6 {
  background-color: hsl(180, 100%, 70%);
}


@media (max-width: 800px) {
  .container {
    flex-direction: column;
  }
}
```


[Properties](https://www.w3schools.com/cssref/index.php):

```css
div {
  width: 100px; // width of the rectangle
  height: 100px;
  color: pink; // color of the inner HTML
  background: black;
  border-radius: 15px; // amount of rounding of the rectangle
}
```

