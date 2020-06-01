---
title: How to Make a Stadium in Blender - 1
date: 2019-08-01 11:22:03
tags: 
- blender
- 3d modeling
---

## Part I

This is a step-by-step tut for makin a stadium like this:

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/25.png)

<!--more-->

1. create a cylinder by shift+A, 3D model and choose cylinder
2. Before you press enter, make sure select Cap Fill Type to be Nothing for this cylinder

![2](/images/How-to-Make-a-Stadium-in-Blender/i/1.jpg)


3. Subdivide Tool for adding more faces on the side of cylinder: in edit mode,  press W and choose Subdivide
4. Smooth surface - Shading - smooth
5. Select the Cylinder , add a modifier -> solidify , Change the value Thick (to whatever that makes sense), turn on Only Rim

![2](/images/How-to-Make-a-Stadium-in-Blender/i/2.jpg)

6. Make sure double sided the object

![2](/images/How-to-Make-a-Stadium-in-Blender/i/3.png)

7. press S for scale, press z on z origin to squeeze the cylinder.
8. In Edit mode, select the sharp edge around the cylinder. Mesh -> Edge -> Bevel to make it a curve

![2](/images/How-to-Make-a-Stadium-in-Blender/i/4.jpg)

9. Then you can use proportion editing to change the shape

![2](/images/How-to-Make-a-Stadium-in-Blender/i/5.png)

https://www.youtube.com/watch?v=ToDeKHZ8TwU
10. Make a tile on the roof

## Part II
Make top roof
![2](/images/How-to-Make-a-Stadium-in-Blender/i/6.png)

1. Select the edge of internal line

![2](/images/How-to-Make-a-Stadium-in-Blender/i/7.png)

2. Press E, S to extend the edge on the same level, just like to create another extended edge, but has a smaller size.

![2](/images/How-to-Make-a-Stadium-in-Blender/i/8.png)

3. Highlight the middle part

![2](/images/How-to-Make-a-Stadium-in-Blender/i/9.png)

4. Press P and choose selection  -  to slide the selected part as another unconnected object

![2](/images/How-to-Make-a-Stadium-in-Blender/i/10.png)

5. Better to make a copy of the new created top
6. Select the all faces, press W and choose subdivision to increase the number of vertices

![2](/images/How-to-Make-a-Stadium-in-Blender/i/11.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/i/12.png)

7. Create an tile object

![2](/images/How-to-Make-a-Stadium-in-Blender/i/13.png)

8. Use particle system. 

![2](/images/How-to-Make-a-Stadium-in-Blender/i/14.png)

choose type hair, advanced and emit from vert.
Rotation is for rotate the entire instances, adjust it by phase.

![2](/images/How-to-Make-a-Stadium-in-Blender/i/15.png)

Then in Render, choose object and use the red cube object to fill it in.

![2](/images/How-to-Make-a-Stadium-in-Blender/i/16.png)

After you create a half side of your roof, use mirror tool to create the other side

![2](/images/How-to-Make-a-Stadium-in-Blender/i/17.png)

Notice that the other size, the rotation of each instance is different from what we have. If we change on of them, it will change the other side of roof. In this case, we need to break the mirror reference.

![2](/images/How-to-Make-a-Stadium-in-Blender/i/18.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/i/19.png)

The thing above doesn’t work for my case, but it’s good to know.
My case is that the two object were using the same particle system.
So we need to break the particle system on mirrored object.

![2](/images/How-to-Make-a-Stadium-in-Blender/i/20.png)

Convert particle as objects

![2](/images/How-to-Make-a-Stadium-in-Blender/i/21.png)

Select the object first, then …

![2](/images/How-to-Make-a-Stadium-in-Blender/i/22.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/i/23.png)
