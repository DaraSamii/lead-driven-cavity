# lead-driven-cavity

This repository contains codes of classic CFD problem "lead-driven Cavity flow". There are to folders cotainiting python and matlab codes for modeling and solving fluid flow in the square region.

In python code folder three different methods are demonstrated, classing interation method, matrix rolling method(using numpy), and matrix rolling method (using cuda GPU-accelerated with pytorch). The performance of these three algorthims are compared and it's shown that GPU-accelerated method is significantly more efficient that other ones.

# lead-driven Cavity class
A generalized class is developed for further analysis and experiments.

## list of tests:
* different Reynolds numbers
* algorithms comparison
* different Height/width ratios

# Results
* the top boudary is moving right with velocity of 1 m/s
* the bottom boundary is moving left with velocity of 1m/s

![u, v, velocity magnitude, vorticity contours](https://github.com/DaraSamii/lead-driven-cavity/blob/master/Python%20Solution%20Code/all.png)


# Matlab exported gifs

![](https://github.com/DaraSamii/lead-driven-cavity/blob/master/GIF%20Output/Cavity_General_V-total.gif)

![](https://github.com/DaraSamii/lead-driven-cavity/blob/master/GIF%20Output/Cavity_General_Stream%20Lines.gif)
