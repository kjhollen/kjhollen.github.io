---
layout: page
type: work
title: substrate
permalink: /substrate/
thumbnail-path: images/grid-thumb.jpg
short-description: processing sketch
work-date: 2012
---

<div class="invisible-margin image-grid">
<div class="col-30-block grid-margin-bottom video">
<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://player.vimeo.com/video/116499505' frameborder='0' webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe></div>
</div>
</div>

substrate is a Processing library developed to prototype gestural interfaces with mobile phones.
The library tracks and moves a collection of pointers on a screen as they are moved and controlled by the movement of mobile devices, through an application built on <a href="http://www.oblong.com">Oblong</a>’s g-speak platform.
Colleagues at Oblong, Zai Chang and Alex Valli, wrote an iPhone application that connects to a server and streams user interaction data, including readings from the phone’s accelerometer.
The Processing library (which I co-developed with <a href="http://www.sansumbrella.com">David Wicks</a>) receives the data and uses it to control the data for a pointer.
Multiple pointers can be added to an application if multiple phones are connected.

The video above shows a demo of the technology in action.
The user moves a cursor by tapping on the phone screen and moving the device.
As the cursor moves, the grid responds by revealing the identity of squares near the cursor.
A double tap reveals the identity of all squares in the grid.

The library was used for a workshop at Eyeo 2012 with Oblong Industries.
