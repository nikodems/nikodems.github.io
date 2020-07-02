---
title: "Real-Time 3D Visualization of The Terrain of Scotland"
published: true
tags: [C++]
---

My honours project was based on rebuilding an existing piece of software into a modern solution. The original software
was called AirSafe - it was developed using Java and Java3D to render the terrain of Scotland, but it was considered outdated
due to Java3D no longer receiving support. I chose C++ and Direct3D as my technologies for rebuilding the program.

A major challenge of the project was the data set used for construction the terrain. The data set consisted of a large
collection of binary files containing floating point values representing 3D cartesian coordinates of points 
collected across Scotland. These files were so large that they couldn't all be stored in memory at once, therefore a 
memory management technique was necessary for reducing memory usage. Another cause of the file size was the loading time
of the data into memory and due to multiple files needing to be loading at once a multi-threading approach was used.

<img src="{{ site.url }}{{ site.baseurl }}/images/finalyearproject/dundee.png" alt="">

The code and further documentation can be accessed below, unfortunately, due to copyright the data files cannot be included.