# community-garden

Community Garden is built for Facebook Hackathon in 2020 by [Yiting Liu](https://yitingliu.com) and Melissa Powers. 
You can play the filter [here](https://www.instagram.com/ar/718215302286771/).

Check out our DEMO video [here](https://www.youtube.com/watch?v=oUpLXvQTNyQ&feature=youtu.be). 

## Inspiration

With more people are into cooking and gardening during the pandemic, we realize gardening is such a cool way to help people come together. This community garden filter is meant to bring people together to create the sense of community we all needed during covid-19, black lives matter movement, and many more. With the reopening in NY reaching phase three, we want to share the joy of being with our friends soon through this filter. 

## Concept 
People help people. It is important to appreciate the community/friend circles we created for ourselves. 

## What it does
The types of flowers change depending on the amount of people in the world AR view. People have to gather together in order to _ unlock _ different types of flowers. It also segments the person(s) and the background to create a dreamy effect. 

## Process
1. Brainstorm to emphasis social and community. We concluded to build a dreamy environment of community garden. More people get to change the type of flowers following them. 
2. 3D model building using Blender (Daisy and Cherry Blossoms are created by Yiting, and two other flowers created by Melissa)
3. Patch Editor work (Yiting created the background and most of the code while Melissa helped.)
- Created customized 3D Particle Patch Asset to mimic the particles system
- Used  3*3 convolution patch to achieve the outline effect in the background 

## Challenges

I wanted to create particle system with the 3D models using the existing particles system in Spark AR. However, the particles system only use 2D materials. Therefore, we created the effect of 3D particle systems by creating different looping animations in terms of the positions and rotations. 

## Accomplishments 
1. I thought of a way to solve the problem of finding four people by photoshopping my face four times and using that to record for my world AR effect. 
2. I used Blender to build 3d flowers and I have been since learning more Blender for more of my work in Spark AR. 
3. I did most of the work in Spark AR in terms of the background effect as well as the tweaking of the 3D particle systems and I am more confident in using Spark AR moving forward. 


## What I learned
It is always good to start with one element and figure out how to program it in Spark and apply it to the rest of the elements. 

## What's next for Community Garden
I will make the background effect more dreamy and try to work on the interaction more to make it more intuitive and interactive. Since it is the world AR effect, the people in front of camera can not see the real-time changes of the environment. I will try to find a way to make it more interactive and immersive. 
