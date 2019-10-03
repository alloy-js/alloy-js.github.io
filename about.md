---
layout: page
title: About
permalink: /about/
---

Sterling combines Alloy with web-based visualizations, providing both basic
Alloy visualization capabilities and a robust platform for the development of 
domain specific visualizations of Alloy instances.

Sterling originates with a smaller project, [Alloy Instances](https://alloy-js.herokuapp.com/),
which allows users to export XML files from Alloy and develop custom visualizations
in the browser. The Alloy Instances tool provides a styling language and sharing
platform that is useful for development of visualizations once a model has been
completed, but it lacks in utility during the iterative modeling process.

Sterling aims to bridge this gap and further build out the visualization and
sharing platforms.

## System Requirements

Sterling *should* run on any system on which Alloy can run. However, I use
Ubuntu Linux and have not done any testing on macOS or Windows (yet). Any
feedback or help getting Sterling up and running on these operating systems
would be much appreciated.

You'll also need a modern web browser, although an internet connection is not
required. Sterling has been tested in both Firefox and Chrome.

## Open Source

Sterling is released under the MIT License. Additionally, Sterling makes use of
the following open source libraries.

* [Alloy](http://alloytools.org/) - An open source language and analyzer for
  software modeling.
* [Dagre](https://github.com/dagrejs/dagre) - A JavaScript library used to
  lay out directed graphs.
* [D3](https://d3js.org/) - A JavaScript library for manipulating documents 
  based on data.
  
## Authors

Currently the only author is me, [Tristan Dyer](https://github.com/atdyer). I'm
a PhD candidate at North Carolina State University in the department of Civil
Engineering, advised by [John Baugh](https://people.engr.ncsu.edu/jwb/).
