# Lane Detection in a Still Frame Image
[Super Data Science](https://www.superdatascience.com) - Practical Project #4

The fourth project in the [Super Data Science](https://www.superdatascience.com) [Python 3 Masterclass](https://www.superdatascience.com/courses/python-3-programming-beginner-to-pro-masterclass) is doing lane detection in a still frame image. Two methods of detection are used.

## Method One
The first method is a simple method of looking for all white objections in the frame. Making the assumption that the lane lines in the photo are white, or nearly white, allows for filtering out everything which is not white. The data left after applying the filter should be the lane lines.

## Method Two
The second method is really an enhancement of the first. It again looks for all near-white objects in the image. However, this time an area of interest is defined. Only near-white objects within the area of interest are considered.