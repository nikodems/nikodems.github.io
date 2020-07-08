---
title: "Audio Programming"
published: true
tags: [C#]
---

As part of the audio programming module, I worked on a music rhythm game. The player controls a rectangular bar which can move across three lanes. These lanes can spawn beats on them and the goal of the game is to hit the coming
beats with the rectangular bar. Each hit gives 1 point and the goal is to get as many points as possible. The game comes with a preset few songs but the actual code can produce beats from any song. 

<img src="{{ site.url }}{{ site.baseurl }}/images/audio/audio.png" alt="">

The beats are created by working on the samples of the music track, and applying a Fast Fourier Transform (FFT) onto them, which is done automatically using Unity's GetSpectrumData() function. The FFT produces a list of the
samples' frequencies, which are compared to the surrounding samples to look for any peaks. These peaks then become beats.

[Source Code](https://github.com/nikodems/audio-programming)