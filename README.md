## Semantic Segmentation to label road pixels

In this project, we'll split up an automotive video into individual camera frames and then we will paint each pixel of 
each camera frame using a Fully Convolutional Network (FCN). We will classify each pixel as either road or not road. This
classification will help other systems in the car to determine where the free space is. 

Following are the important files:
- helper.py contains the helper functions used in main.py
- main.py is the file responsible for training the model.
- project_tests.py
- Newest inference images from runs folder (all images from the most recent run)

Due to limited resources, training could not be done for a longer period of time. Main goal of the project is to demonstrate the
understanding of semantic segmentation. 

Here is the sample output:

![alt text](https://github.com/UsmanIjaz/SDC_Semantic_Segmentation/blob/master/runs/1535459706.0558352/um_000086.png
 "Sample Output 1")

![alt text](https://github.com/UsmanIjaz/SDC_Semantic_Segmentation/blob/master/runs/1535459706.0558352/um_000070.png
 "Sample Output 2")

![alt text](https://github.com/UsmanIjaz/SDC_Semantic_Segmentation/blob/master/runs/1535459706.0558352/um_000092.png
 "Sample Output 3")

![alt text](https://github.com/UsmanIjaz/SDC_Semantic_Segmentation/blob/master/runs/1535459706.0558352/um_000005.png
 "Sample Output 4")
