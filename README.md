# Traffic-Signs-Detection
The problem statement of this project is to detect and localize traffic signs with yellow + red colors in a set of 25 street images.  
This problem can be solved either by traditional computer vision tools, such as edge
detection and image processing, or it can also be solved using deep learning models such as
Faster R-CNNs.  
Using deep learning for this problem is an overkill and will lead to unneeded complications.
Also, to get acceptable results, a big enough dataset should be available to train the model.
If we can find such a dataset, we will need to filter out the images with yellow + red signs
only, which will most probably shrink the size of the dataset dramatically. We can use the
full dataset, but we will have to do image processing at the end to get only signs with
yellow + red colors. Not to mention the time needed to train the model in the first place.  
That is why I decided to solve the problem with traditional computer vision and image
processing techniques.  
## Proposed Solution  
Traffic signs have standard shapes, such as triangles, circles, squares, etc. The signs
provided in the 25 images are mainly triangles and circles. Thus, we have an important
feature to search for in the image, which is the shape. However, shape is not sufficient on its
own since we can find triangles and circles in the images that are not signs. Yet, we already
know the colors of the signs we are searching for. Hence, my method will be based on color
and shape.  
More details can be found in the report file.
