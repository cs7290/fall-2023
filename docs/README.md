# intro to html

## minimal web page

* [Anatomy of an HTML document](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started#anatomy_of_an_html_document) -- mdn
  * Note: You need to click the link in the right-hand menu bar -- it doesn't get there automatically
  * I've saved that demo into "./index.html"
  * To view it locally in your browser...

Start the local development server...
```
python -m http.server
```
Then browse to: http://localhost:8000

## number-guessing game

* This is an interactive game built with JavaScript
  * [A first splash](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash)
  * It's a simple application but the source code might seem a little daunting
  * [source code](https://github.com/mdn/learning-area/blob/main/javascript/introduction-to-js-1/first-splash/number-guessing-game.html)
  * It's worth glancing at the source code to get an idea of how things work
  * selecting elements with `document.querySelector()`, adding event listeners
  * creating elements dynamically with `document.createElement()`
  * responding to user interaction with `element.addEventListener()`
* Start the server and browse to: http://localhost:8000/number-guessing-game.html

## CSS Selectors

* [CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors#types_of_selectors) (mdn)
* the most common: 
  * type (element, e.g., div, h1, etc.) -- no prefix
  * class (element's class attribute) -- uses the "." prefix

## bootstrap 5

* [bootstrap home page](https://getbootstrap.com/) -- getbootstrap.com
  * More than a library -- it's a "toolkit" for responsive websites
  * Note the Examples
  * It's all front-end CSS and JavaScript
  * Even the simple examples aren't all that simple (as you can see with view source)
  * But the sites are responsive (try it) and concerned with browser compatibility
  * And bootstrap5 can be customized (if you're a front-end developer)
* [bootstrap5 tutorial](https://www.w3schools.com/bootstrap5/index.php) -- w3schools
  * These examples are super simple.
  * This a highly recommended place to start out.
  * id (element's id attribute) -- uses the "#" prefix

## embedding observable

* [Embedding notebooks](https://observablehq.com/collection/@observablehq/embedding-notebooks) -- Observable collection
  * [Embedding](https://observablehq.com/@observablehq/embeds?collection=@observablehq/embedding-notebooks) -- notebook
* Demo...
  * the Observable notebook: [Bar chart transitions](https://observablehq.com/@d3/bar-chart-transitions)
  * the iframe embed -- Browse to: http://localhost:8000/iframe.html
  * the runtime embed -- Browse to: http://localhost:8000/runtime.html
  * Don't worry about "Runtime with React" -- that's for front-end developers
* One of my github-pages demos, which uses bootstrap: https://pbogden.github.io/quakes
