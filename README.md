# hello-world
The first file on my git hub.

## Part 1: Imaging Technique Inspiration

The inspiration is from a YouTube video "Playing with Perlin Noise in p5.js - generative art with lots of options, plus wave convections", at:

[Playing with Perlin Noise in p5.js](https://www.youtube.com/watch?v=CSMcrKouQ3o)

The effect of ripples attracts me, which is triggered by dragging the mouse on the screen, and several ripples are stimulated to generate:

![The stimulation of mouse movement.](Noise1.png)

With time going on, the tiny random scale ripples grow larger, when they hit the edges of canvas, they get a force and go back as growing larger. Finally, the image gets engergetic with massive ripples:

![As time goes by, the effects of massive ripples.](Noise2.png)

As I plan to draw several dots in the assignment, the use of Perlin Noise in this reference can benefit the drawing of random but less messy figures by time. After deciding to use Perlin Noise, I watched these tutorials:

| Insights | Link |
| ----------- | ----------- |
| The basic rules of Perlin noise: A normal distribution of values between 0 and 1| [I.2: Introduction - Perlin Noise and p5.js Tutorial](https://www.youtube.com/watch?v=Qf4dIN99e2w) |
| The one dimension Perlin noise and how to visualise it | [I.4: Graphing 1D Perlin Noise - Perlin Noise and p5.js Tutorial](https://www.youtube.com/watch?v=y7sgcFhk6ZM&list=PLRqwX-V7Uu6ZV4yEcW3uDwOgGXKUUsPOM&index=5) |
| The two dimension Perlin noise and visualise it by a gray scale added on each pixel| [I.5: 2D Noise - Perlin Noise and p5.js Tutorial](https://www.youtube.com/watch?v=ikwNrFvnL3g&list=PLRqwX-V7Uu6ZV4yEcW3uDwOgGXKUUsPOM&index=6) |

## Part 2: Coding Technique Exploration

Perlin Noise is a tool in p5.js which can benefits the change of values to be stable by its smooth curve of value:

![The smooth of change in Perlin Noise](Noise4.jpeg)