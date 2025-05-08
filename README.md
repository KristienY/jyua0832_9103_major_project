# Week9 Quiz

## Imaging Technique Inspiration

This artwork resembles a **clock**, where each number position is replaced by small human figures. At every hour mark stands a couple—a man in a tailcoat and a woman in a gown—shown in various dance poses. 

The piece is **moving with symphonic music (BGM)** and allows interaction: Press LEFT and RIGHT ARROW KEYS to adjust rotation speed. HOLD mouse to pause. RELEASE mouse to resume.

The entire artwork spins **as a circle**, and by leveraging **the visual effect of fast rotation**, the figures appear to be **ballroom dancing in smooth, elegant motion**. 

This illusion of movement created through circular motion is the key technique I want to incorporate into my assignment.

[Website Link](https://openprocessing.org/sketch/563436)
![An image 1](assest/Phenakistiscope1.png)
![An image 2](assest/Phenakistiscope2.png)

## Coding Technique Exploration

The technique is super easy but visual effect is amazing.

1. Draw a circle  
use __createCircle()__ function

2. Assign each figure with fixed angle by using sine/cosine functions to calculate its (x, y) position
use __let angle = (TWO_PI / count) * i__ function

3. The entire circle is rotated as a whole by updating the base angle. This creates the illusion that the figures are dancing fluidly around a center point.
use __getPointOnCircle(centerX, centerY, radius, angle)__ function

4. The press button
use __function keyPressed()__, __function mousePressed()__, __function mouseReleased()__.
