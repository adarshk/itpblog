---
layout: post
title: "Project Development studio week 1"
description: ""
tags: [Project Development Studio]
comments: true  
share: true
---

###Concise Description

To create a computer graphics library that is based on Disney's [12 principles of animation](https://vimeo.com/93206523). By using the library to write a few lines of code, be able to make a character out of any primary shape for example a sphere, cube , circle, triangle etc. Through this process, I also expect to learn more about graphics programming (OpenGL). This will be developed in C++ possibly using Cinder.

#### Who is it for?
It is mainly for myself with the possibility of being used by others if the development gets to a stage where the code is polished.

#### What do you want as a user (even if it is for yourself) when interacting with the work to ?

#### -- Feel
		I want the user to feel in control of what they create.
#### -- Do
		I want to be able to let the user create animations with only by importing the library and writing a few lines of code. The user will be able to tweak and play around with the parameters. These animations would have otherwise needed to be done in animation software like After Effects or Blender.

#### -- Know
		The user doesn't need to know much about animation while getting results that may have taken a lot more time otherwise. The idea is to make it approachable to creating animations using code.
		
#### What is the “problem” you are trying to solve and what is your recommended solution
When I was learning processing the problem I found is that it is really hard to create simple pleasing animations using code. Either knowledge of the way graphics work was required or other animation software like Blender or After Effects had to be used to achieve the same result. This meant that these softwares had to be learnt and the same skills couldn't be carried across different softwares. The library will help in prototyping with animations by making it more approachable even though the user may not have previous experience with animation. 

Solution:

1. Study other animation libraries and understand how basic animations are performed.
2. Prototype using Cinder or Processing.
3. Start by creating animations for 2D shapes
4. Study animations for 3D shapes and think about parameters necessary for the user to be in control of the shapes.
5. Make the code into a library. 

#### Why use code instead of creating animations in ........?
Code allows the applications to have a lot more flexibility. The user doesn't need to be restricted to a video format. With code the prototyping can be much faster while also allowing the user to perform and draw advanced graphics and animations.

#### What are the opportunities that you see in the problem space?
There are a lot of opportunities in this space. 
1. To able to give any user who is either learning to write code or experimenting to create graphics/animations the ability to perform animations with very little setup and requirements.
2. To be able to create animations that previously would require the use of other animation software that had their own learning curve.
3. The possibility of letting the user learn coding and animation through experimentation and prototyping.

#### What are the general challenges in the problem area and what do you think will be your specific challenges
The general challenges in the area is that its difficult to create animations that look both pleasing in a small amount of time using with little knowledge about the process. The user has to go through a training phase of first understanding the process and software before making something. Depending on how skilled the user is, this can take anywhere from few hours to weeks.
Challenges:

1. Leaning the theory of graphics and animations can take up time.
2. Understanding what animations need to be performed needs to investigated by looking at other animations, artists and lots of experimentation.
3. Making a library that would help with quick prototyping while providing decent results.

#### What research (with references) have you done so far (articles, related projects, materials etc)

- https://vimeo.com/93206523
- I have been reading books on computer graphics during the summer
- I also been prototyping with simple code however I haven't made too much progress.
- I have also been looking at other frameworks like [cinder](libcinder.org), [openframeworks](openframeworks.cc) and [processing](processing.org)

###What are the technical, interactional requirements for your project
Technical : Theory of graphics, OpenGL, C++, understand how animations are performed.
Interactional : Understand graphics and animations by looking at the code of creative frameworks like cinder/openframeworks/processing/threejs.

1. What kind of algorithms are required for the animations?
2. Can I learn by looking at other libraries that are out there?
3. How do I ask and receive feedback if this was used by other animators or developers?

####What are your criteria of success (how will you know you have succeeded) & how do you plan to evaluate this success?
By the end of the process if I am able to understand more about graphics, animations and be able to perform those with minimal effort of coding.
I plan to let others who have little experience with coding to use the library and see if they are able to use it and create animations by just reading the documentation.

#### Timeline

Week 1 - Read theory behind simple animations and prototype

Week 2 & 3- Continue prototyping with Cinder

Week 4 & 5 - Write code to perform animations for one primary 2d shape

Week 6 - Get feedback

Week 7 - Tweak according to feedback

Week 8 - Write code to perform animations with other primary shapes

Week 9 & 10 - Prototype with 3d shape

Week 11 - Get feedback and tweak for other shapes

Week 12 - Package code into library

Week 13 - Cleanup

Week 14 - Presentation