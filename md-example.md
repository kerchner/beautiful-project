---
layout: page
title: Markdown-based page example
subtitle: Subtitle goes here
bigimg: /img/start.jpg
---

## Here is where we can insert an image:

![GW Data Science logo](/img/gwdsp.png)

## How about a link?

And of course some text, and maybe [a link to https://datasci.columbian.gwu.edu/](https://datasci.columbian.gwu.edu/)

## Or some code?

Some code might go here:

```
x <- 5 # Here's some R code
```

What if I just paste the HTML for a plotly plot?

We can do it with a line of markdown that looks like this (without the slashes - I haven't solved that problem just yet...):
```
\{\% include jupyter-basic_bar.html \%\}
```
{% include jupyter-basic_bar.html %}

Attempting to embed an RShiny app:

<div class="iframe_container">
  <iframe width="800" height="700" scrolling="yes" frameborder="no"  src="https://kerchner.shinyapps.io/rshiny-test/"> </iframe>
</div>
