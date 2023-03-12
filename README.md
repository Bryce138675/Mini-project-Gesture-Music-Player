Gesture Music Player
GitHub Link: https://github.com/Bryce138675/Mini-project-Gesture-Music-Player 

1.Importing libraries

•	Import Pygame --- Pygame is a cross-platform set of Python modules designed for writing video games. It includes computer graphics and sound libraries designed to be used with the Python programming language.

•	Import os --- The OS module in Python provides functions for creating and removing a directory (folder), fetching its contents, changing and identifying the current directory, etc.

2.Hand keypoint detection

Reference to a project to present a PPT through gesture recognition (https://blog.csdn.net/dgvv4/article/details/12368273)

•	Video capture (Get the computer camera, Width of the image, Height of the image)
•	Create music dataset (5 songs)
•	Draw a line on the camera and make a gesture with your hand above the line to trigger
•	Hand recognition module configuration (Up to 2 hands detected)
•	FlipType--- Flip the image so that the computer image is a mirror image of our own
•	Draw a line and make a gesture above the line to trigger
•	Draw a finger movement mapping area
•	Counts how many fingers are cocked and returns a list where 1 means the finger is cocked and 0 means bent
•	Get the xyz position of 21 key points
•	Setting the mapping area (x,y)
•	Hand centre coordinates

3.	Control music

The following code uses the pygame library to play music (https://blog.csdn.net/RNG_uzi_/article/details/98315639)

•	Work on key finger points to determine which fingers are cocked--- returns a list where 1 means the finger is cocked and 0 means bent

•	Use fingers to play music

a.	thumb and forefinger--- Watermelon Sugar
b.	thumbs, forefinger and little finger--- I Knew You Were Trouble
c.	thumbs and little finger to play--- Adore You
d.	forefinger, middle finger, ring finger, little finger--- As It Was
e.	Use forefinger and middle finger to play--- Golden

•	Use fingers to control music

The following codes refer to the music player. (https://blog.csdn.net/txr152111/article/details/119213827)

a.	forefinger and little finger--- pause music
b.	thumb, middle finger, ring finger and little finger---unpause music
c.	thumb, forefinger, middle finger, ring finger and little finger---stop music

4.	Display and Release

5.	Feedback 

I have only used five gestures to play music. After that I will use more gestures to play music. I will also improve the music player by using gestures to play the previous and next song and to adjust the volume.
