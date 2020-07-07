---
title: "Tools Programming"
published: true
tags: [C++]
---

As part of a fourth year module, I worked on a game tool program, used for aiding development. The module was based on
taking a basic windows application which rendered objects and terrain from a database, and adding features which would aid
development. 

<img src="{{ site.url }}{{ site.baseurl }}/images/tools/overview.png" alt="">

I worked on an AI pathing feature which allowed the user to insert objects into the scene, after which a path would be
generated between them using Catmull-Rom splines. The idea behind this was to allow developers easer implementation of 
AI pathing for features such as cutscenes or set pieces.

<img src="{{ site.url }}{{ site.baseurl }}/images/tools/path.png" alt="">

The second feature I worked on was a system for moving the objects in the scene in the editor. Selecting an object in the
scene would pop up a window with the positional values, which could then be edited and the changes would be seen in real-time.

<img src="{{ site.url }}{{ site.baseurl }}/images/tools/popup.png" alt="">

Only code related to the calculating and rendering of the AI paths, as well as the editor window were created by me. The
program was created with C++ and MFC.
