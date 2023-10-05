# 05-Dashboard

## Reading

* [Dashboard/2](https://observablehq.com/@mbostock/dashboard/2) 
* [Interactive Plot Dashboard](https://observablehq.com/@ambassadors/interactive-plot-dashboard)

## attribution

Reminder...

* attribution is very important
  * forking is attribution
  * importing is attribution
* copy and paste can be indistinguishable from plagiarism

## Dashboard/2 -- how it works...

https://observablehq.com/@mbostock/dashboard/2
```
<div style="
  background: #fff;
  display: grid;
  height: ${screen.height / screen.width * 100}vw;
  grid-template-areas: 'a b' 'a b' 'a b' 'c c';
  grid-gap: 10px;
">
```
* screen.height (actually, it's window.screen.height)
* [window.screen](https://developer.mozilla.org/en-US/docs/Web/API/Window/screen) -- mdn
* [window.innerWidth](https://developer.mozilla.org/en-US/docs/Web/API/Window/innerWidth) -- mdn
* [div element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div) -- mdn
* [element.clientWidth](https://developer.mozilla.org/en-US/docs/Web/API/Element/clientWidth) -- mdn
* [CSS grid layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout) -- mdn
* miscellaneous considerations
  * browser support
  * mobile devices
  * containers vs 
  [SVG](https://developer.mozilla.org/en-US/docs/Web/SVG) elements
  vs [canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) elements

## Interactive Plot dashboard -- how it works

* https://observablehq.com/@ambassadors/interactive-plot-dashboard
* currentState is a [viewof](https://observablehq.com/@observablehq/a-brief-introduction-to-viewof)
  * this is the data that updates when you click on the map, triggering the changes
* [Introduction to views](https://observablehq.com/@observablehq/views)

## quakes

Embedding demo (we'll look at it in detail next week)

* [quakes](https://pbogden.github.io/quakes/)
* static web page served from github-pages 
* uses [bootstrap](http://getbootstrap.com)


# PMA updates (added during class on 5 Oct)

Stakeholder next week? -- No -- next week we put things in github pages sites

* Notebooks discussed in class...
  * https://observablehq.com/@class/hw04-hahehola 
  * https://observablehq.com/d/18b08c576010735f -- Bridget and MK 
* STORY
  * Seasonal signal dominates
  * Long-term downward trend on energy usage is evident on multi-year time scale
  * Significant variation (values and data availability) between buildings and meters
  * Outstanding questions...
    * there are quite a few questions about what could be causing these various signals
    * sustainability of the business -- revenue vs costs and long-term goals
    * sometimes multiple meters for a building
    * relationship to weather (TBD)
