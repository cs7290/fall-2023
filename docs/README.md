# 06-Embed/docs

<<<<<<< HEAD
This directory is configured (in the repo settings) to be served by github pages
at this base URL: https://cs7290.github.io/fall-2023/
=======
This directory is configured (in the repo settings) to be served with github pages
here: [https://cs7290.github.io/fall-2023/](https://cs7290.github.io/fall-2023/)
>>>>>>> 486a6646648c26a2de17bd20703df93182adb0ed

## minimal web page

* [Anatomy of an HTML document](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started#anatomy_of_an_html_document) -- mdn
  * Note: You need to click the link in the right-hand menu bar -- it doesn't get there automatically
<<<<<<< HEAD
  * I've saved this demo in the local file `./index.html`
  * By convention, `index.html` is the default file for any web server -- if it's there, it'll be served
  * And the `.docs` directory is default directory for github pages for this repo.
* So that's the file that github pages serves at the base URL: https://cs7290.github.io/fall-2023/
* To view it locally in your browser, which is better for development because changes are instantaneous:
  start the local development server...
  ```
  python -m http.server
  ```
  Then browse to: http://localhost:8000

## your portfolio

You can create a [github-pages](https://pages.github.com/) site for any repo that you own.
It'll be served from http://username.github.io/reponame

NOTE: If you do create a github-pages site, I do NOT recommend using the github-pages Jekyll templates. 
It's easy to create something that's pretty. And you can use them if you want, but it quickly gets complicated.
You've been warned;-)

## javascript demo

* The github pages site: [number-guessing-game.html](https://cs7290.github.io/fall-2023/number-guessing-game.html)
  serves the code from the
  [first splash](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash) on mdn.
* It's an interactive game built with "vanilla" JavaScript
  * [A first splash](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash)
  * Although it's a simple application, the source code might seem a little daunting.
  * [source code](https://github.com/mdn/learning-area/blob/main/javascript/introduction-to-js-1/first-splash/number-guessing-game.html)
  * It's worth glancing at the source code to get an idea of how things work. Some of the basics...
    * selecting elements with `document.querySelector()`, adding event listeners
    * creating elements dynamically with `document.createElement()`
    * responding to user interaction with `element.addEventListener()`
* To serve it locally, start the http server and browse to: http://localhost:8000/number-guessing-game.html

## CSS Selectors

* The code above uses CSS selectors, which we'll be using a lot.
* [CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors#types_of_selectors) (mdn)
* The three most common, which you really need to know: 
  * type (for HTML elements such as div, h1, etc.) -- has no prefix
  * class (for an element's class attribute) -- uses the "." prefix, there may be many class attributes in any document
  * id (for element's "id" attribute) -- uses the "#" prefix, there can be only one in any document
* Note: CSS is a royal pain to debug! But it's super powerful and supported (mostly) by all browsers. 
  Welcome to the world wide web;-)
* [Mozilla Development Network (mdn)](http://developer.mozilla.org) is your friend, and the authoritative 
  resource to help you figure things out.
=======
  * I've saved that demo into "./index.html"
* The github pages site: [https://cs7290.github.io/fall-2023/](https://cs7290.github.io/fall-2023/)
* To view it locally in your browser (better for development because it's instantaneous)...

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
* Or browse to 

## CSS Selectors

* [CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors#types_of_selectors) (mdn)
* the most common: 
  * type (element, e.g., div, h1, etc.) -- no prefix
  * class (element's class attribute) -- uses the "." prefix
>>>>>>> 486a6646648c26a2de17bd20703df93182adb0ed

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
  * the iframe embed
    * github-pages: [https://cs7290.github.io/fall-2023/iframe.html](https://cs7290.github.io/fall-2023/iframe.html)
    * locally -- browse to: http://localhost:8000/iframe.html
  * the runtime embed
    * github-pages: [https://cs7290.github.io/fall-2023/runtime.html](https://cs7290.github.io/fall-2023/runtime.html)
    * locally -- browse to: http://localhost:8000/runtime.html
  * Don't worry about "Runtime with React" -- that's for front-end developers

## quakes

One of my github-pages demos, which uses bootstrap: https://pbogden.github.io/quakes
