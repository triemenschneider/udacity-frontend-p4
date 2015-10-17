## How to start

Just open `index.html` in a browser. In the following overview select the pizza-subpage.


## What I did...

### ...in index.html

* compressed the pictures, especcially `pizzeria.jpg`
* got rid of the google-webfont
* replaced the external `style.css`-stylesheet by inline-CSS
* inlcuded the google `analytics.js` async

### ...in main.js

* `"use strict";` (line 21)
* rewrote `changePizzaSizes()` (line 430)
* stored `randomPizzas.length` in a variable outside the for-loop (line 449)
* stored `#randomPizzas`-div in a variable outside the for-loop (line 466)
* replaced `document.querySelectorAll()` by `document.getElementsByClassName()` (lines 448, 500)
* stored `document.body.scrollTop / 1250` in a variable outside the for-loop (line 502)
* dynamically calculating the amount of background-pizzas to fill the screen (line 528)

### ...in style.css

* added `will-change: transform;` to `randomPizzaContainer`-div
* added `transform: translateZ(0);` to `mover`-image