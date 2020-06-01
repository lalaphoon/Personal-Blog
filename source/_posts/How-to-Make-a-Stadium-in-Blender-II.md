---
title: How to Make a Stadium in Blender - 2 (Final)
date: 2019-08-02 11:22:03
tags: 
- blender
- 3d modeling
---

## Part 3

Create a model for the bar

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/1.png)

<!--more-->

Combine faces by pressing F

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/2.png)

Add my bar as a particle evenly to the face.
How to do it:

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/3.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/ii/4.png)

https://blender.stackexchange.com/questions/50695/emit-hair-particle-from-center-of-face/50697

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/5.png)

The constraint is to make all face evenly (all face should has the same size, and same shape), then you can apply particle on face evenly.

## Part 4 - Final

镂空墙壁 - https://jingyan.baidu.com/article/ed2a5d1f74aa9409f6be17dd.html

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/6.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/ii/7.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/ii/8.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/ii/9.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/ii/10.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/ii/11.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/ii/12.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/ii/13.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/ii/14.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/ii/15.png)

Use the same technique to create another template - use number 0.95 for all last steps (ignore the number on the screenshot)

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/16.png)

Select the lines, E, Z to create a face along Z axis, give a depth. Apply Solidfy modifier to give thickness.
Then combine two templates like this

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/17.png)

Better to make you model align to the same line - This below is not good.

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/18.png)

Create another cylinder that has even face around the stadium, then you can apply you new created network to the wall by using particle system

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/19.png)

My setting for the particle around the green wall is

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/20.png)
![2](/images/How-to-Make-a-Stadium-in-Blender/ii/21.png)

My wall instance’s frame is

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/22.png)

(Blue goes up)
If your don’t satisfy the alignment issue, you will have this problem

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/23.png)

The complete is this below: greenllines are showing parent-child and group relationship.
Parent and child has a line, all grouped objects will be labeled in green.
Parent is looking good to organize in hierarchy chard
Group is some modification that you can do to a group of objects (see more details in Links for TuT)

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/24.png)

Used Bisect and select by vertices, it finally fixed as

![2](/images/How-to-Make-a-Stadium-in-Blender/ii/25.png)
