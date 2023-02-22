# vgg-object-detection-example
A course project using vgg for swimming pool detection.

### AA_assignment2_final
a jupyter notebook implementing image preprocessing, vgg training and evaluation. Since we did not have access to GPUs, I made use of three memory control approaches:
- train_test_split on file names and load images when feeding into the model; 
- resize into smaller images before training; 
- apply "imagenet" as initial weights.

Here below shows the best and the worst detections with prediction in red and true box in blue.


   <img src="https://github.com/kun126/vgg-object-detection-example/blob/main/best%205.png" width=80% height=80%>
   <img src="https://github.com/kun126/vgg-object-detection-example/blob/main/worst%205.png" width=80% height=80%>


### sample images
examples of the input satellite images, the original folder containing 14964 images.

### metadata
a dictionary of the coordinates of swimming pool for each image.
