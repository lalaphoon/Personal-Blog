---
title: A Small Town - OpenGL Project Summary
date: 2018-01-18 17:54:37
tags:
- OpenGL
- computer graphics
- game
- c++
- project
---

[See it on Github](https://github.com/lalaphoon/CS488-Project)

Hi, this is the game that I created for CS488 Spring 2017 OpenGL C++ Final project to complete 10 objectives : Modelling the scene, UI, Particle System, Sound, Static Collision detection, Transparency, Reflection Map, Texture Mapping, Shadow Mapping (imperfect), Lens Flare.

The game took me 1.5 weeks to plan and study, and another 1.5 weeks to actual implement it. The game was purely implemented by math including linear algebra, vector and matrices; And shaders in OpenGL C++. No extra game engine was used. Edited: And I got **Honorable Mention** for this project!

<!--more-->

{% raw %}
<button onclick="window.open('/files/CS488_Final_Report.pdf')">Check Final Report</button>
{% endraw %}

Here is a video about it:

{% video <iframe width="560" height="315" src="https://www.youtube.com/embed/Y29Be31nX_o?rel=0&amp;showinfo=0" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe> %}

Here are some fun screenshots:

You can see your life situation in the life bar. The red colour means you are in dangerous!
 ![1](/images/small-town/1.png)
 The greener bar indicating you are about to win.
![2](/images/small-town/2.png)

There are some images on my process of work.
I was really frustrated when I got failed on texture mapping. And after fixed my texture mapping, I got this!

![3](/images/small-town/3.png)

I was really happy when it’s getting better!!

![4](/images/small-town/4.png)

Adding the third person camera and particle system.

![5](/images/small-town/5.png)

It’s really beautify when I apply multi-texture on plane.

![6](/images/small-town/6.png)

It was really starting from scratch. You can see the result of a plane with multi-texturing mapping on it, a textured model - earth and the skybox.

Adding water plane with reflection map from skybox.

![7](/images/small-town/7.png)

I was trying to create a view after rain. You can see the road is filled with puddles from the rain.

![5](/images/small-town/8.png)

Skybox is used to implement the reflection map on water. You can see the result here. Water plane is another plane with blending map.

Hopefully you can see the normal mapping here.

![5](/images/small-town/9.png)

and here.

![5](/images/small-town/10.png)

There were also a few obstacles stopped me.

Skybox, by just changing a string for the image file name. It’s like I was lucky to use the only one correct group of images for the skybox.

![5](/images/small-town/11.png)

Shadow was there, but it’s gone after I added normal mapping for the earth.

![5](/images/small-town/12.png)

And it’s not a perfect shadow. That’s why I chose to add normal mapping to make up my failure on shadow. Some strange shadow here:

![5](/images/small-town/13.png)

There is a scene from bird view. Far plane was clipped behind the houses.

![5](/images/small-town/14.png)

You have to put your camera near to the ground to see the Lens flare. Or just go back to those houses. The reason is that I set up the light source (sun) is really close to the scene. So you can see lens flare when you have a longer distance from the sun.

![5](/images/small-town/15.png)

The final scene.

![5](/images/small-town/16.png)

Thank you very much for reading this. Hopefully, you would like this game.
