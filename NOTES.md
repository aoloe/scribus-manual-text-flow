# Notes

## Flowing around text

On july 17, 2016 garry [writes in the forus](http://forums.scribus.net/index.php/topic,2127.msg9548.html#msg9548)

Here's the basic technique:
- Draw your text frame and put your text in it;
- Draw your image frame and put an image in it (or you can use whatever other object you want);
* Make sure that your image frame is at a higher level (or on a higher layer) than the text frame (text only flows around stuff that is "above" it.);
* Select the image frame and go to Properties Palette;
* Choose the "Shape" tab (or the "Group" tab if your image is in a group);
* Select one of the Text Flow options, Contour Line is best (for reasons I won't go into here);
* Move the image frame around to place it where you want.

If the text is too near the image then:
* Select the image frame and go to Properties Palette;
* Choose the "Shape" tab (or the "Group" tab if your image is in a group);
* Press the "Edit..." button;
* Check the "Edit Contour Line" box in the Node Editor dialog that has just popped up (very important as you're flowing around the Contour Line);
* Adjust the nodes as appropriate for what you want to do;
* When finished, press the "End Editing" button in the Node Editor dialog.

And that's it. If you're not happy with the flow then move the frame or re-edit the contour line.

