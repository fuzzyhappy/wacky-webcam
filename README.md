# wacky webcam
by Evan Wang

## What is it
Wacky webcam is an application which runs a variety of image processing techniques on the user's live webcam feed. Kernelized webcam then displays the resultant feed in a 640x480 `JFrame` with a menu bar which gives the user the ability to save their capture as a `.png` file, if desired. The user may also choose what kind of image processing (half-tone, kernel, or gray-scale). 

This project was made in the 4 days after the author didn't get the score he wanted on his calculus 3 final.

## How to run
You can run kernelized webcam by typing `java WebcamProcessor` into your terminal, assuming you have the prequesite libraries installed (`sarxos' webcam-capture` and `slf4j-nop`). A `JFrame` displaying a live feed of your webcam should then be launched, as long as no other application is currently using your webcam and as long as `kernel.txt` is formatted correctly. 

`kernel.txt` should be formatted with the first line containing an integer `n`. The subsequent `n` lines should then contain each row of the intended kernel, with each one of the `n` `float`s from each row being seperated by a space.
