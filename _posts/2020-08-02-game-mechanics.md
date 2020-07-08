---
title: "Game Mechanics"
published: true
tags: [C++]
---
For the Game Mechanics module, I worked on a projectile manipulation system inside the Unreal Engine. The system allows the user
to change the behaviour of the fired projectiles. The system has several options: bouncing, piercing, splitting and increasing
the number of projectiles. When bouncing is active, the projectile can bounce a couple of times before disappearing, otherwise on
collision the projectile will disappear.

Piercing allows the projectile to pass through a couple of enemies. When splitting is active, on collision with an enemey the 
projectile will split into two projectiles. Increasing the number of projectiles is self-explanatory. All of the options
can be active at once, meaning the projectiles can bounce, pierce and split. 

A video showcasing the project can be seen here: [Youtube](https://www.youtube.com/watch?v=kh-_71wuPf4&t=)

[Source Code](https://github.com/nikodems/game-mechanics)