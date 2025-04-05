---
title: thisIsWeekThree 😱
published_at: 2022-11-04
snippet: An example of a blog post.
disable_html_sanitization: true
allow_math: true
---

# Homework 3a

## RR's sketch

<iframe id="flying_frying" src="https://www.flyingfrying.com/"></iframe>

<script type="module">

    const iframe  = document.getElementById (`flying_frying`)
    iframe.width  = iframe.parentNode.scrollWidth
    iframe.height = iframe.width * 9 / 16 + 42

</script>

**Visual**
The colors are mainlly white and yellow with a slight shadow to make the egg stand out from the whole white background.
Also, the egg floating on the surface gives some funny feelings when I looked at it.
**Interactivity**
I think mainly in this sketch is about a moving fried egg, so it may serve the function that capture audience's attention when it moves. To make it move in the sketch, random() may be used and it should have the appearance of TAU in the code.

## My sketch

**Visual**
My definition about cuteness for this project is mainly around soft edges, light colors and floating animations.

**Interactivity:**
I think it returns from the idea that playing tag, when we were young and naive. helps the audience recall their childhood, everyone once played tag and clearly understood the mechanics of running and chasing.

# Homework 3b

## How I will use each of the following concepts in my AT1:

**Variables**
THe animation is mainly around a combination of dynamic-tracking variables. Some crucial variables that lead to the entire part of the sketch is the canvas element and its 2D rendering context, they provide the foundation for all drawing operations. I'll also use variables for animation flows, positioning, and visual styleing.

**Iteration**
There will be a for loop that iterates over each pixel across the canvas width to create the sine wave pattern by calculating the y-position for each x-coordinate. ALso, i'll use .forEach for waves to make it iterate over each wwave object to render multiple waves and give the water a layered appearance with different colors and dynamics.

**Arrays**
My intention for using an array in the sketch is to contain parameter for the water waves, and each element in the array would be an object with their own properties, like frequency, amplitude, color and speed. Altogether, they're visually creating a multiple distinct waves.

**Classes**
I'm about to use class to create an interactive object that just operate bottom part of the canvas, by assigning its initial position to x and y variables, and those two variable can be varied depend on the cursor. At the same time, the fish will be drawn in each animation frame.

`class Fish {
  constructor(x, y) {
    this.x = x;
    this.y = y;
    this.targetX = x;
    this.targetY = y;
    this.speed = 0.1;
    this.size = 40;
    this.angle = 0;
    this.turnAngle = 0;
    this.swimOffset = 0;
    this.lastMouseX = x;
    }
}`

## Embed a rough draft of your AT1 on your blog.

<iframe id="final" src="https://editor.p5js.org/def-ijk/sketches/kWccOFm8p"></iframe>

<script type="module">

    const iframe  = document.getElementById (`final`)
    iframe.width  = iframe.parentNode.scrollWidth
    iframe.height = iframe.width * 9 / 16 + 42
</script>

**How well did you achieve cuteness in the visual, sonic, and interactive domains?**
Those elements above work together to create an interactive underwater scene. In that, waves are continuously animated across the top of the screen, a fish follows the mouse whenever the mouse is below the water. All of those create a interactive animation with physics-like movement and visual appeal.

**What communities and learning resources did you draw on to do the bulk of your learning for this project?**
I've gained all the fundamental knowledge about animation or interactivity in the p5.js referrence pages. Also there are some other advanced concepts about JavaScript, I have learnt them on youTube and in case some weird method or rough concepts which are hard to comprehend, I used Claude.ai to get some helps and figurd them out.

**What aspects have you enjoyed the most about this process? What have you found to be most surprising?**
Like what I referred on the introduction day, I've just started coding recently, so every concepts or definitions that I reach made me feel strange, weird and excited, or even overwhelmed sometime. Surprising the most is that coding is not as hard as what people think, also its application is truly immersive in current life. Therefore, every knowledge about coding is enjoyable for me during the whole process.

**What aspects have you struggled with the most? What have you found the most confusing?**
The most struggling part that I had to deal with is the sub methods which I need to use in the whole sketch. It was really time consuming to find them out and get to comprehend their concept and used them properly.
