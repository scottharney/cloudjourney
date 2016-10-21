# Introduction

This is a presentation I prepared for
the [Louisiana IT Symposium](http://www.efmevents.com/2016/louisiana/) on
October 5, 2016. 

```
.
├── 5points.png
├── ASG-AppMap-slide1.png
├── ASG-AppMap-slide2.png
├── ASG-AppMap-slide3.png
├── asg_slide_bg.png
├── cloudjourney_slides.html
├── cloudjourney_slides.org
├── reveal.js
├── Starting your IT organization's journey to Cloud IT.pdf

```

# How to use

Either clone the repo or download a zip of it.  Unzip to a local directory and
open cloudjourney_slides.html.  You must unzip it and navigate into the created
directory.  If you just double click on the cloudjourney_slides.html without
unpacking it you'll get a flat outline without the presentation styling
elements.

You can press 'f' to get full screen.  press 's' to get speaker notes.  It works
like any typical powerpoint but within any web browser.

# How I made this.

I don't like working in anything heavy like powerpoint and instead create my
outline in [org mode format](http://orgmode.org/)
using [http://spacemacs.org/](spacemaces) .  I can write in simple plain text
with minimal markup and manage it as a git repo.  I actually started the initial
outline on my phone.

To convert the outline into a working presentation, I
used [reveal.js](http://lab.hakim.se/reveal-js/#/) with a slighly modified
theme.  I
used [ox-reveal](https://github.com/yjwen/org-reveal/blob/master/Readme.org) to
manage the export from org mode to reveal.js .  Reveal can also use markdown but
I just prefer to write markup in org mode since that's what I use for all of my
note taking and outlining.
