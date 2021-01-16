---
layout: post
title: Why and how you should reduce the size of your photos (MacOS only).
---

With the ability to take photos anywhere and at anytime a lot of images can accumulate really quick. Nowadays presumably most of the photos will be taken by a smartphone. If you take the photo the device will have to convert your image (maybe do some AI stuff and improvements) and store it as a JPG.
Due to limit resources in computational power and time (you don't want to wait a few seconds to be able to  take the next photo) the algorithm (and its settings) for converting the raw image to JPG is chosen to be fast but not to deliver highly compressed images.

Yet if you moved your photos to your PC you have the time and computational power to run a second compression in order to reduce the storage space you need for your photo collection.

The tool I use on my Mac is [ImageOptim](https://github.com/ImageOptim/ImageOptim) which is free, open source and really easy to use.
I don't want to go into details how to set up this tools just make sure that you setup ImageOptim to leave the metadata untouched.

To illustrate the benefit I took all the photos my wife and I took in 2020 and measured the density (defined as MB/Megapixel) before and after the size reduction.

![image_reduction]({{ site.baseurl }}/images/image_reduction.png)

This reduction has been done at a 85% quality setting in ImageOptim.

**In total 68% of space (4.42 Gb) have been saved.**

One now could argue that space is de facto unlimited nowadays and cheap as ever but this is something I will address in a later post ;-)

At last some example to give an idea how these images look before (upper part) and after (lower part) the optimization.

Before (3.2 MB):
![Before]({{ site.baseurl }}/images/PXL_20210111_112354971.jpg)

After (1.4 MB):
![After]({{ site.baseurl }}/images/PXL_20210111_112354971_reduced.jpg)

