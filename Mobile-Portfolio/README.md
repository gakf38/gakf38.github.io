### Changes to index.html
* Removed the web fonts link
* Inlined and minified the `style.css` file
* Added a `print` media tag to the `print.css` link
* Added `async` tag to the Google Analytics scripts
* Moved the the `perfsmatter.js` link to the end of the body
* Optimized all the images, including a resized pizzeria image (pizzeria-100.jpg)

### Changes to main.js
* Changed `switch` statement in `changePizzaSizes` function to calculate newWidth in percentages instead of pixels
* Used `querySelectorAll` to pull all `randomPizzaContainers` at once and not within the for loop of `changePizzaSizes`
* Moved `scrollTop` outside of for loop in `updatePosition` function to avoid synchronous layout
* Modified calculation in for loop of `updatePosition` to use precalculated `scrollTop` value

### Steps to run
1. Download complete resource
2. Open index.html
3. See all the optimizations :)
