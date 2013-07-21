GameFX
======
David Catuhe has recently released a simple & powerfull WebGL 3D engine named Babylon.JS: http://blogs.msdn.com/b/eternalcoding/archive/2013/06/27/babylon-js-a-complete-javascript-framework-for-building-3d-games-with-html-5-and-webgl.aspx

While he was writing his engine, we’ve built a small team made of Pierre Lagarde, Sébastien Pertus and I to imagine a framework on top of Babylon.JS to help developers building games in a very simple way. This framework mainly targets people that are not very comfortable with all 3D concepts and gaming loop yet. But it could be useful also for more advance developers as we’ve tried to implement some boring tasks for you. 

We just finished a v0.1 of the client part. By the way, v0.1 means that this is far from being completed. :) But we’d like to start sharing with you what we’ve done so far, listen to your feedbacks and continue/enhance it in the next weeks.

What are the features in the v0.1?
You’ll see that we’re already handling a lot of tasks for you. The idea is to take default decisions that would match 80% of what you would probably like to do in your game. We’re hiding a lot of the complexity. Of course, a possible drawback is that you won’t be able to do exactly what you want with our framework by default. But this is not a very big problem as you can override most of the default decisions we’ve made. And it’s JavaScript: you can do whatever you want to tweak it! ;-)

The framework currently includes the following features’ list:

- a game world/assets manager/game entities concepts to abstract most of the BabylonJS complexity. They will handle the async loading, the initialization of the BabylonJS engine, the gaming loop, the collisions between the game entities and so so. 
- a keyboard manager that will control a specific game entity with a default inertia algorithm setup. 
- a virtual touch joystick that will be able to control a specific game entity or to control the camera of the game (for FPS lile games)

You’ll see also that we’re then creating a default camera & a default light for you. You can then start learning 3D concepts in a simple way and change our default parameters to really match your inspiration later on.

You can find some tutorials on David Rousset's blog: http://blogs.msdn.com/davrous
