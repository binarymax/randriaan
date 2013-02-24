#Randriaan

##Victory Boogie Woogie SETUP competition

###Instructions:
1. start chrome or firefox
2. open the file randriaan.html
3. wait until it looks pretty
4. click 'Print' to save the image

###Sample:
Two samples are provided as randriaan_circles.pdf and randriaan_lines.pdf.  These samples rendered, respectively, for 84 minutes and 51 minutes!  However, after 3 minutes or so, a likeness becomes apparent.

###How it works:
A simple algorithm places a random shape of a random color on the test canvas.  A fitness algorithm decides if the resulting test canvas looks more similar to the original Victory Boogie Woogie.  If it does, then the shape is saved.  If it does not, then the shape is discarded.  Repeat until the observer is happy enough to press the 'Print' button.  The observer can also change the shape style - but note when the shape style is changed, the current image is lost and the rendering starts again from the beginning.

###Motivation:
Victory Boogie Woogie is the last work by Piet Mondriaan.  It is unfinished.  This program never finishes, the observer simply decides when he or she is satisfied.

###Technical:
I chose to use HTML/SVG and Javascript, so that when released there would be nothing to download and it should run on any machine with a recent version of Chrome or FireFox (I tested the program with both browsers on Ubuntu 12.04 and Windows 7).  Printing the page to PDF or similar format retains the SVG vectors, so there is no pixelation in a printed image.  This is an ideal choice for when it is hanging next to the original masterpiece :)

###Size and Method:
A fully commented version of the program can be found in randriaan_commented.html.  In order for the program to fit in one file, I had to sacrifice some browser compatibility - I was not able to load the javascript-worker script from the same page on Opera or Safari.  Additionally, it is worth noting that even though I embedded a copy of Victory Boogie Woogie on the page, the code runs independent of this particular image.  In fact, it would be straightforward to swap in any image into the algorithm and have it render.  I have another version of the program that does just that, but removed that code for this demo for brevity.  After the competition is over, I plan on releasing that program so that anyone can run the program using the image of their choice, and it should support all modern popular browsers.

###### *Made with love by Max Irwin (http://binarymax.com)*
