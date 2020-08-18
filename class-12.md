## Reading Day: 12
# Chart.js, Canvas
Chart.js is a JavaScript plugin that uses HTML5's canvas element to draw the graph onto the page. **It's a plugin that makes using bar charts, line charts, pie charts easy.** The reading states 'incredibly easy' but I'll be the judge of that when I use it. Javascript code is included in this reading. I cloned the repo so I could have the files. The demo includes 3 different charts created with vector based graphics. Wow, I hope it is as straight forward as it claims to be.

## Basic Usage of Canvas
The **canvas** element is used when insterting the cool graphs from the last paragraph. It has two attributes: **width and height.**
Canvas allows you to create shapes, draw paths, and render them on the screen. It can get into some precise drawing using **cubic bezier curves** which will allow you to create almost any shape.

## Applying Styles and Colors to Canvas
fillStyle = color: is used when filling shapes. strokeStyle = color: Sets the style for shapes' outlines. The next example caught my attention using strokeStyle. The example used two variables i and j to generate a unique RGB color for each square, and only modify the red and green values. The result looked like a color palette.

![Gradient](images/canvas-fillstyle.jpg)

The canvas color tools are very powerful. I liked the **arc method** to draw circles and the transparency and alpha channel tools. Getting a handle on designing this way seems far away. Being a visual artist I'm used to tools to select from. The obvious example is photoshop which I've worked with for over 20 years. I would love to use these new tools that seem very foreign right now. But then the first time I opened photoshop was a new experience.

The ability to use gradients and shadows on objects to acheive 3d images is pretty remarkable. I'm sure there are places on the web to view images created using canvas. Not having a 'paint bucket' seems a bit confusing. However I just had an 'a-ha' moment. A consistency I've noticed while learning JavaScript is you must first map out your code; line by line. Using canvas and creating images that way is no different. You would start with a sketch and work from that. I would approach creating visuals using canvas that way.

![Circles](images/Canvas_radialgradient.jpg)

## Drawing Text
Okay, I'm really impressed by the rendering of canvas. Styling text inlcude **font, textAlign, textBaseline, and direction values. It is a lot to take in right now. I took another step of knowing what I didn't know. And now I feel like there is so much more I need to know.

[<== Back to Table of Contents](index.md)

images used from article.
https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors