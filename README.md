# Static Comp 1

## Overview
Static Comp 1 provides an opportunity to create a static page showcasing a topic with a simple box and image carousel layout. We have creative license over the color pallete, photo(s), icons, and text content so long as it doesn't completely stray from the spirit of the original comp shown below.

Original Comp: 
![original comp design](images/static-comp-challenge-1.jpg)

## Result 

I began with a mobile styling, 320x568 pixels. I took advantage of the default block styling of the `<article>` elements which make up the boxes below the #intro `<section>`. The image carousel sits below and is given 100vh so when the user scrolls down the image carousel takes up the full screen.

![mobile styling](images/js-comp2-mobile.png)

Finally, at screens above 790px in width, the image carousel is given a width of 40% and inline-block display, the main flexed box section is given a width of 60% and floated to the left, thus allowing the carousel to join it inline with the main section. From here, further media queries for larger screens serve only to bump up the font size for easier reading.

Final Product:
![full screen styling](images/js-comp2-fullscreen.png)
