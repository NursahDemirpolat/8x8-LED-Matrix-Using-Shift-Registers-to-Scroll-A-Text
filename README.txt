# 8x8-LED-Matrix-Using-Shift-Registers-to-Scroll-A-Text

List of Materials:
-8x8 LED MATRIX


Code Description
First, I created a character class for my project, so I can take the characters in the sentence I want to write from here and show them with an 8x8 led matrix. 
Then I created a text array for the sentence I want to write (NURSAH B1605.010037). 
I called the ShiftText folder that I created for floating text in the loop. 
I extracted the number of columns from each character address in the ShiftText folder and copied 7 bytes to the buffer array. 
Then I showed the buffer array at the x (column) and y (0) points that I specified with writeSprite. 
I turned off the LEDs specified in SetColumn. In the for loop, I turned on the LEDs in 150 milliseconds and showed them on the screen. 
Finally, I increased the string value and made the text slide continuously.
