---
layout: post
title:  "Skeuomorphic book cover in CSS"
date:   2022-01-18 11:11:00 +0530
categories: web
permalink: /blog/:year/:month/:day/:title
excerpt: I was inspired by the look and feel of books in Apple Books. Created the same effect in CSS for the blog. 
---

I was quite inspired by the way Apple Books shows their bookshelf. They turn every book into a hardbound which greatly enhances the visual appeal. It was clearly being done by adding a layer of styling on top of the book cover because the ebook I imported did not contain the physical attributes.

![Apple Books](/assets/blog/images/apple-books.png)

If I could manage to draw a linear gradient on top of the book in CSS, that should do the trick. I began by drawing a linear gradient in Figma, but the controls wouldn't let me go very granular. So I moved back to code. 

I started with a simple CSS linear gradient:

```
    background: linear-gradient(to right, 
                    #000 0%, 
                    #FFF 100%);
```

My goal was to recreate the emboss effect that light would have on a hardbound when the source is on left. The gradient stops had to be very close to each other.

Took me a few iterations, but this is where I was fairly happy:

```
    background: linear-gradient(to right,  
                    rgba(0,0,0,0.02) 0%,
                    rgba(0,0,0,0.05) 0.75%,
                    rgba(255,255,255,0.5) 1.0%,
                    rgba(255,255,255,0.6) 1.3%,
                    rgba(255,255,255,0.5) 1.4%,
                    rgba(255,255,255,0.3) 1.5%,
                    rgba(255,255,255,0.3) 2.4%,
                    rgba(0,0,0,0.05) 2.7%,
                    rgba(0,0,0,0.05) 3.5%,
                    rgba(255,255,255,0.3) 4%,
                    rgba(255,255,255,0.3) 4.5%,
                    rgba(244,244,244,0.1) 5.4%,
                    rgba(244,244,244,0.1) 99%,
                    rgba(144,144,144,0.2) 100%);
```
{% jsfiddle wxLdkta1/4 result,html,css iframe default 480px "100%" %}


That's all. Check out the effect on my [Bookshelf](/bookshelf).