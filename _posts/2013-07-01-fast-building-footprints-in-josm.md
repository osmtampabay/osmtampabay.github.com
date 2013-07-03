---
layout: post
date: 2013-07-01 12:43:16 EDT
title: "Fast building footprints in JOSM"
categories: blog
author: Coleman
author_url: http://colemanm.org
---

One of the neatest things to see on OpenStreetMap, something that truly makes the map look rich and detailed, are buildings. They add tons of context and visual presentation quality to the data. And used in conjunction with [Pushpin](http://pushpinosm.org/) in the field, the footprints become the "base" for adding other details like height, floors, addresses, and businesses. The trouble is, mass editing building footprints is pretty tedious, and lots of buildings are complex shapes that can be painstaking to trace.

This short guide shows a couple of tools you can use within JOSM to make tracing detailed buildings much more simple.

Once you have JOSM running, go to the Preferences &rarr; Plugins tab. You'll need to install the [BuildingsTools](http://wiki.openstreetmap.org/wiki/JOSM/Plugins/BuildingsTools) plugin to make the initial tracing faster than simply drawing ways. The building tool (keyboard shortcut: `b`) is instrumental in fast tracing, and using that in concert with the **Extrude** tool (shortcut: `x`) can ramp up speed in tracing.

This video shows how to use the extrusion tool to quickly and accurately extract these buildings:

<iframe src="http://player.vimeo.com/video/69505541?title=0&amp;byline=0&amp;portrait=0&amp;color=c9ff23" width="500" height="282" frameborder="0"> </iframe>

With these tools, plus their corresponding keyboard shortcuts, you can make quick work of even intricately-shaped building outlines:

<iframe src="http://player.vimeo.com/video/69516467?title=0&amp;byline=0&amp;portrait=0&amp;color=c9ff23" width="500" height="281" frameborder="0"> </iframe>

When drawing other polygonal, orthogonal shapes (for things like parks, landuse delineations, basketball courts, etc), I even use this same process, then just replace the `building=yes` tag with the appropriate attribution.
