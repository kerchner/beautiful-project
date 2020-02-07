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

Embedding a Google Sheet:

<div class="iframe_container">
<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSu5plR4pBvk-cYi-uH7xeaWlhPXcHwzHZY51-4VpuvRhQbHzpHE1LuqHHwIBjN8bLNvFH7oS8j-2j2/pubchart?oid=1600182453&amp;format=interactive"></iframe>
  </div>
