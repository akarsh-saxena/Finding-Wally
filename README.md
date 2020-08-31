# Finding-Wally

A solution to the infamous puzzle "Where is Wally/Waldo?". I have implemented two approaches to find the position of Wally in a puzzle.

<br />

1. <b>Template Based Approach</b>:

    In this approach, the user have to provide the photo of Wally along with the puzzle. It is a sort of pattern matching approach which also requires the photo to be found.
  
<br />
  
2. <b>Deep Learning Based Approach</b>:

    An object detection algorithm was trained on an annotated dataset of these puzzles. The model used for detection is "Faster RCNN with Inception v2". This allows us to detect Wally from any image without requiring the user to input Wally's image that is to be found.
