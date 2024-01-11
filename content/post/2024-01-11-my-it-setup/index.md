---
title: My IT setup
author: Chris Littleboy
date: '2023-08-14'
slug: my-it-setup
categories: [Research]
tags: [Technology]
---
I love an IT setup blog, so here is mine!
I am fully aware that this makes me a bit strange.
But, as someone who works with computers every day, there is a vague relevance to my work.
Personally, the process of honing my setup has wasted a lot of my time over the years.
Reading others' struggles with this I enjoy because I can see that it isn't just me frittering away time tinkering.
If I had known then what I know now I would have wasted less time and money on the wrong solutions.
If this blog helps someone else waste less time, then great.
If not, hopefully an obsessive IT tinkerer will get a sense of togetherness in our strange hobby.

## Hardware

I use spatial data, so need slightly more oomph than the average user.
Currently I have a desktop computer with 32GB RAM, an NVIDIA 3060 ti GPU, a Ryzen 7 8-core processor, 500GB of internal storage and 5TB of external storage.
When I've saved the £350 to do so, I'll buy another 64GB of RAM and a 2TB nvme disk.
At the university there is a server (256GB RAM, 40 cores) that I can run parallel code for "big data" on.
My personal laptop costs £250 and is there to do emails, netflix, and run windows when I need it to.
I've got two normal-size screens, an external webcam, a loud but satisfying mechanical keyboard, and an ageing ACER mouse.

## OS

I run the latest Ubuntu OS.
Choosing a desktop Linux OS itself undoubtedly wastes a lot of time.
Every time I update, I need to fiddle with my GPU driver to get the second monitor working again.
Regularly I will need to run some unintuitive command to get my ethernet running again.
Doing this is annoying but manageable in itself, but finding out how to fix these issues takes A LOT of time.
In the two years since I switched from windows, I have probably spent two weeks troubleshooting problems that I would not have run into had I not switched.

But through troubleshooting how to do things that happen under the hood on my windows laptop, I now understand how computers work better.
This has undexpected benefits in the way I code and work.
For anyone who wants to work with servers, starting on a linux OS will make the learning curve less steep.
And I am yet to find a problem which demands a proprietary software not on linux to solve.
Not to say that MS Word wouldn't make things easier, especially to collaborate.

Whatever I run, it runs better on Ubuntu. 
There is a significant performance difference.
What I don't like on Windows is the need to sign in to an account to do anything.
Data going back and forth from these accounts wastes network bandwidth and RAM, slowing everything down.
And most important, it is free and unrestricted.

## Software 

- R

R is my bread and butter.
I use R Studio, the dedicated IDE, which has everything laid out where you need it.
My theme of choice is Cobalt, but any dark theme with linting is, in my view, what you need.
I do use the tidyverse for data frame manipulation, but mostly I try to use base R when possible which tends to be quicker.
And the packages which I use all the time are *terra* and *sf* for spatial analysis, and *ggplot2* for visualisation.
Learning R takes time, and I am constantly finding out ways of writing my code in a more concise and legible way.
In my experience, learning by constantly tackling new practical problems is the quickest way to improve fast.

I use R Markdown for articles, together with *bookdown*.
This has become indispensable due to Zotero bibliographic software integration.
I'm not sure if this saved me time with my PhD thesis - there was a learning curve which took time. 
But the whole process of integrating references, data, figures and text in the same folder made my academic work far more manageable.
My results are replicable, and I now use it all the time and can't imagine a better way.

- QGIS

I use QGIS a lot.
Mainly I'll use QGIS to get a quick map to show a layer that I'm interested in with a baselayer.
A bit of exploratory analysis, to understand the data that I'm working with.
Any full analysis, or figures, I'll do using R, but QGIS is a good starting point.

- VS Code

A text editor with lots of extensions.
For any project that is not in R, or for working on remote PCs, I'll use VS Code.
Also for batch-editing text files.

- GIMP

I started using GIMP when I started working with raw satellite imagery data, to make nice true colour images from space.
There is a world of possibilities, and I'm just getting started.

- GiHub desktop

Most projects I will start with an R project, and host this on GitHub if there is an element of collaboration involved. GitHub desktop is a nice GUI so I don't have to bother with git terminal commands (though I'm sure I'll get into this eventually).

- Overleaf

Browser-based so I'm not sure if it counts. But I've started using this recently to make nice/different looking text-based documents. There are lots of good templates, and I'm getting to grips with LaTeX through it.

- Google drive

I begrudgingly use Google drive. It has cheap-ish storage with an API to interface with code. This has become important for satellite imagery. But it is slow and annoying (why can't you see how large a folder is?! Or how many files are in a folder without scrolling down?!)

And that's about it. Next on the aspirational purchase list is an e-ink tablet for reading articles and books so I can remove a bit of glare from my life.