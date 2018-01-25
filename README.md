# Drawing in the browser
#### How HTML5 canvas can be great, easy & performant for data visualization

This repository contains the slides and examples that are discussed in my short workshop about doing data visualization with HTML5 canvas.

See the examples folder for the following complete code files from which I am using snippets in my slidedeck:

### 1a | Create a canvas
Creating a straightforward canvas and getting the context to draw on

### 1b | Create a retina sharp canvas
On (Mac's) retina screens, images created by canvas look a bit blurry. This example shows a simple way to counter that, by increasing the canvas size, but shrinking it back into the original width and height

### 2 | Drawing basic shapes
Contains the code for all the basic shapes discussed in the workshop: rectangles, text, circles, lines and paths

### 3 | Drawing curved paths
Contains the code to create a Quadratic and Cubic bezier curve

### 4 | Breathing Earth
Recreate one week of my [Breathing Earth visualization](http://www.datasketch.es/img/april-nadieh.jpg) in a simple loop over all the datapoints

### 5 | Linear animation
How to "mimic" a linear animation by using the idea of frames and `requestAnimationFrame`

### 6 | Eased animation
With a few updates to the linear animation and d3's interpolation and/or easing functions, you can also create an "eased" animation

### 7 | Other changes
An example of how, instead of position, opacity and radius of a circle can be changed