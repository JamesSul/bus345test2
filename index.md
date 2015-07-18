---
title       : Why MIS?
subtitle    : Chapter 1
author      : BUS 345
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : solarized dark      # 
widgets     : [bootstrap, quiz]            # {mathjax, quiz, bootstrap}
ext_widgets : {rCharts: [libraries/nvd3]}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- &radio

## What is Moore's Law?

1. Computer processors become twice as fast every 18 months.
2. _The number of transistors we cab fit on a processor chip doubles every 18 months._
3. Bandwidth on the interenet doubles every 18 months.
4. The number of users on the internet doubles every 18 months.

*** .hint
Gordon Moore is a co-founder of Intel, which makes processors.

*** .explanation
Moore's law is commonly misunderstood to apply to the speed of computers, which is technically incorrect (althought it captures the sense of his principle).

*** =pnotes
Append ?presentme=true to url

--- .class #id 

## Effect of Moore's Law

[!["Gordon Moore" by Steve Jurvetson from Menlo Park, USA - Moore Fish. Licensed under CC BY 2.0 via Wikimedia Commons](./assets/img/Gordon_Moore.jpg)](https://commons.wikimedia.org/wiki/File:Gordon_Moore.jpg#/media/File:Gordon_Moore.jpg)

The cost of data processing, communications, and storage is essentially zero.

______

[![Groupwise Quota](./assets/img/groupwise_quota.png)](https://webapp.usm.maine.edu/confluence/display/kb/How+to+deal+with+a+full+mailbox)


*** =pnotes
When I came to USM, we were using groupwise and not gmail.
How much space is on the maine.edu gmail drives? 30Gb and keeps going up
Why are we still doing this?

--- .class #id
## Transistor Prices

<div id = 'chart1' class = 'rChart morris'></div>
<script type='text/javascript'>
    var chartParams = {
 "element": "chart1",
"width":            800,
"height":            400,
"xkey": "year",
"ykeys": [
 "cost" 
],
"data": [
 {
 "year": "1983",
"cost":           3923 
},
{
 "year": "1985",
"cost":         902.95 
},
{
 "year": "1988",
"cost":          314.5 
},
{
 "year": "1997",
"cost":          17.45 
},
{
 "year": "2002",
"cost":           0.97 
},
{
 "year": "2005",
"cost":           0.05 
},
{
 "year": "2015",
"cost":           0.01 
} 
],
"pointSize":              0,
"lineWidth":              1,
"id": "chart1",
"labels": "cost" 
},
      chartType = "line"
    new Morris[chartType](chartParams)
</script>
