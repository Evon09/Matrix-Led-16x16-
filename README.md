# Matrix-Led-16x16
Sketch for Arduino, Esp8266 and others to create an image in a led matrix of any size

<h1>First step</h1>

In an image editor make a drawing of any size equal to your matrix, and then save

Second step

Open the program "lcd-image-converter" va file open and select your image.

Third step

Go to options and select convert, in type put color in image put block size in 24 bit, depending on your matrix change the line scan direction.

Fourth step

Press the show preview button, copy the code and replace it in the arduino code.

Congratulations just compile and it's working.

Ps: Depending on your matrix you will have to use a different script (it was my case), so I left it annotated in a text file, when converting, just put in the custom script option and paste the custom script

Ps: This video explains much better https://www.youtube.com/watch?v=Q1iVtLQOZOImas my code is changed so you can use a button to go through the loops so it's your choice.

(Hope this helps)
