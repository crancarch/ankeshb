+++
content_img_path = ""
date = "2019-06-23T23:00:00+05:30"
draft = true
excerpt = "Implementing PDF.js in site to render and parse pdf's as html so that UX is optimised for viewing PDFs."
layout = "post"
subtitle = "Implementing PDF.js in site to render and parse pdf's as html"
thumb_img_path = ""
title = "Using PDF.js in Hugo"

+++
I was faced by the issue of whether how to display resume's pdf from sidebar menu to an end user 2 days from now. As the first solution I implemented it the old school way by uploading the pdf and linking it through `href`  tag.

But the UX seems not to be sane with this, a user has to click two times and open pdf in an external environment than the web browser.

I found a library named [pdf.js by mozilla](https://mozilla.github.io/pdf.js/) which lets one render and open pdf in the browser environment thus improvising on UX front. I wasn't familiar with implementing js libraries in a server environment and this got me nowhere when trying to integrate it. 

On research I finally got a solution working : cloning the bare minimum required assets to project root's location. Though it isn't considered as best of practises, it just worked. You can find how it'd work out on the issues page linked.

<blockquote class="embedly-card"><h4><a href="https://github.com/shermisaurus/ankeshb/issues/2">Add PDF.js support to open pdf links parsed as HTML in desktop browsers. · Issue #2 · shermisaurus/ankeshb</a></h4><p>PDF.js hasn't proper starter guide to get things going on one click and proper explanation for the project. Issue : The pdf doesn't gets rendered through the viewe.html file located in build directory of PDF.js. Solution : Implementation...</p></blockquote>
<script async src="//cdn.embedly.com/widgets/platform.js" charset="UTF-8"></script>

Gotta try to use npm and a build tool to properly use library as it's recommended by the official pdf.js docs before it's late. Made it an

 I personally like following good practises as recognized by the community and believe they are one of good traits to follow being an open sourcer.