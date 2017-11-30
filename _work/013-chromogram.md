---
layout: page
type: work
title: Chromogram
permalink: /chromogram/
thumbnail-path: images/chromogram-thumb.png
short-description: data visualization
work-date: 2006
columns: 3
---

Chromogram is a visualization technique for revealing patterns in a large sequence of text data. While working with Martin Wattenberg and Fernanda Viégas, we applied this technique to individuals' contributions to Wikipedia. The first three letters of an article title or comment are respectively mapped to a hue, saturation, and brightness range, revealing patterns of editing and repeated tasks.

<div class="invisible-margin image-grid">
<div class="image-inline" style="text-align:center;">
<img style="margin-left: auto; margin-right: auto;" src="{{ site.baseurl }}/images/chromogram-color-guide.png" />
</div>
</div>

Chromogram revealed some alphabetical editing sequences for many editors, in particular editing bots (including user Pearle, shown above). Wikipedia bots assist editors by performing clean-up tasks for articles that have been marked with various flags by editors.

<div class="invisible-margin image-grid">
<div class="col-30-block">
<img src="{{ site.baseurl }}/images/chromogram-pearle.png">
</div>
</div>

The color mapping algorithm is applied to two data points in edits to Wikipedia: article titles and comments accompanying the edit. Toggling between views revealed different patterns. In the sample below, an editor appears to alternate between editing similarly titled pages and an alphabetical sequence of pages.

<div class="invisible-margin image-grid">
<div class="col-30-block">
<img src="{{ site.baseurl }}/images/chromogram-titles.png">
</div>
</div>

Switching to the comment view (see below) reveals the the user alternates between participating in discussions with other editors and then contributing the geography section of articles. The editor creates map images and then links to them in other articles, which is a common pattern for many contributors.

<div class="invisible-margin image-grid">
<div class="col-30-block">
<img src="{{ site.baseurl }}/images/chromogram-comments.png">
</div>
</div>

Martin and Fernanda have a detailed description of Chromogram & our study of Wikipedia editors <a href="http://hint.fm/projects/chromogram/">on their site, hint.fm.</a> &gt;&gt;