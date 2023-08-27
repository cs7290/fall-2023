
# Plot

Introduction to [Observable Plot](https://observablehq.com/plot/)

## intro

* [What is Plot?](https://observablehq.com/plot/what-is-plot)
  > Observable Plot is a free, open-source, JavaScript library for visualizing tabular data, 
  > focused on accelerating exploratory data analysis.  It has a concise, memorable, yet expressive API, 
  > featuring scales and layered marks in the grammar of graphics style.
* [Why Plot?](https://observablehq.com/plot/why-plot)
  > Observable Plot is for exploratory data visualization. It’s for finding insights quickly.
  * Plot has a well-designed API that builds on D3, which makes it remarkably extensible.
* [Getting Started](https://observablehq.com/plot/getting-started)
  * This link provides installation instructions for various web technologies (e.g., React, Svelt, Vue, etc.)
  * The first two sections tell you to about using Plot in Observable and in vanilla HTML -- we'll use both of these.
  * We won't use React, Svelt, Vue, etc. -- these are for app development (they show up in the web-dev course).
* [Plot](https://github.com/observablehq/plot) -- github

## theory

* [A Layered Grammar of Graphics](https://www.tandfonline.com/doi/abs/10.1198/jcgs.2009.07098?journalCode=ucgs20)
  * Hadley Wickham defines a graphical grammar as the fundamental principles of the art/science of statistical graphics
  * It builds on previous work and describes the implentation in R's ggplot2
* [grammar of graphics (summary)](https://info5940.infosci.cornell.edu/notes/dataviz/grammar-of-graphics/)
  * This web page is a concise summary of Hadley Wickham's article
  * [Plot from ggplot2](https://observablehq.com/@observablehq/plot-from-ggplot2) -- compares Plot and ggplot2
* [Introducing D3-scale](https://medium.com/@mbostock/introducing-d3-scale-61980c51545f)
  * This article builds on the theory, providing Mike Bostock's perspective, as well as his goals for D3.
  * [Visualization publication dataset](https://observablehq.com/@observablehq/vispubdata)
  * [D3](https://observablehq.com/@d3) -- observable collection
* [D3 or D3.js](https://github.com/d3/d3) -- github
  > D3 (or D3.js) is a free, open-source JavaScript library for visualizing data. 
  Its low-level approach built on web standards offers unparalleled flexibility in authoring dynamic, 
  data-driven graphics. 

## basic elements

* [Plot](https://observablehq.com/plot) Main page links to key sections in the API reference docs
  * [Plot](https://observablehq.com/plot/what-is-plot) API reference docs
  * The topics in the left-hand navigation bar are the features (basic elements)...
* [plots](https://observablehq.com/plot/features/plots)
  * Typically, calling `Plot.plot()` with the desired options will render a plot
* [marks](https://observablehq.com/plot/features/marks)
  * [marks are geometric shapes](https://observablehq.com/plot/features/marks#marks-are-geometric-shapes)
    * Plot doesn’t have chart types; instead, you construct charts by layering marks.
    * the mark constructor takes two arguments: data, options (each mark has its own data)
  * [marks have "channels"](https://observablehq.com/plot/features/marks#marks-have-channels)
    * Commonly used channels include horizontal position "x" and vertical position "y"
    * Other optional channels: fill, fillOpacity, stroke, strokeOpacity, strokeWidth, opacity, title, href, ariaLabel
    * channel values can be column names, functions of data or arrays
    * channel values can also be an object with a transform method that is passed the data array and returns an array
  * [marks are layered](https://observablehq.com/plot/features/marks#marks-are-layered)
    * you can use multiple marks to construct various kinds of plots
    * "the big advantage over chart types is that you can compose multiple marks of different types into a single plot
    * [Plot.marks()](https://observablehq.com/plot/features/marks#marks) is a convenience method for composing marks
  * each mark object has a "plot" method for rendering a plot
* [Scales](https://observablehq.com/plot/features/scales)
  * "Scales convert an abstract value such as time or temperature to a visual value such as x→ or y↑ position or color."
  * Demo using [gistemp](https://observablehq.com/@observablehq/plot-temporal-scatterplot)
* [Projections](https://observablehq.com/plot/features/projections)
  * "A projection maps abstract coordinates in x and y to pixel positions on screen."
* [Transforms](https://observablehq.com/plot/features/transforms)
  * Transforms derive data as part of the plot specification.
* [Interactions](https://observablehq.com/plot/features/interactions)
  * This section has documentation for pointing (e.g. tooltips)
  * It also has sections on experimental functionality such as zooming & animation
  * Documentation points to github issues and community discussions.
  * You can also see the experiments by Mike & Fil!
  * And you can upvote the things you'd like them to add in the future!

## Explorations

Explorations collection has two semi-guided tutorials -- weather & penguins

* [Plot Explorations](https://observablehq.com/collection/@observablehq/plot-explorations) -- collection
