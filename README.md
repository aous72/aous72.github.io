# OpenJPH Blog

[OpenJPH](https://github.com/aous72/OpenJPH) is an open-source implementation of HTJ2K encoder and decoder; the code is developed by Aous Thabit Naman, and is released under the 2-clause BSD license.  HTJ2K is also known as JPEG2000 Part 15, ISO/IEC 15444-15, and ITU-T.814. The .jph file extension has been designated to this format, from which the name of the implementation is derived.

The interested reader is referred to the [short HTJ2K white paper](http://ds.jpeg.org/whitepapers/jpeg-htj2k-whitepaper.pdf), or the [extended HTJ2K white paper](https://htj2k.com/wp-content/uploads/white-paper.pdf) for more details on HTJ2K. [This](https://kakadusoftware.com/wp-content/uploads/2019/09/icip2019.pdf) paper explores the attainable performance on CPU, and [this](https://kakadusoftware.com/wp-content/uploads/2019/09/ICIP2019_GPU.pdf) paper for decoding on a GPU.

## Javascript of OpenJPH

OpenJPH can be compiled to Javascript.  For a demo, see [**this**](https://openjph.org/javascript/demo.html).  This demo also shows decoding a single HTJ2K image at multiple resolutions, a feature known as resolution scalability.  The decoding process involves decoding a prefix of the file; i.e., decoding only the first x bytes of the file -- the number of bytes that need to be decoded is detailed in the demo.html page.

Another project of interest is the [openjphjs](https://github.com/chafey/openjphjs) project, developed by [Chris](https://github.com/chafey);  at [this URL](https://chafey.github.com/openjphjs/test/browser/index.html) you can find a nice online demonstration of javascript-based HTJ2K encoding/decoding, with a wealth of features and user-selectable options.

## htj2k.com Website

A newly launched website that shares interest in HTJ2K is the fittingly named [htj2k.com](https://htj2k.com/) website. 
