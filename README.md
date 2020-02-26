# Custom object detection multi class to predict fruits in custom dataset 

This is an example showing the use of Mask RCNN in a real application, creating multiple class for classify some objects
this post in medium will help you to create an computer vision application with multiple class.



[Medium blog post](https://medium.com/@bernardo.acaldas/using-maskrcnn-to-predict-tropical-fruits-in-custom-dataset-4f079d05fbe1)



## Results

![orange prediction](https://github.com/bernardcaldas/object-detection-custom-maskrcnn/blob/master/tropical/new-images/orange.png)





## Installation
From the [Releases page](https://github.com/matterport/Mask_RCNN/releases) page:

Clone this repository https://github.com/matterport/Mask_RCNN.git

Install dependencies

pip3 install -r requirements.txt
Run setup from the repository root directory

python3 setup.py install
Download pre-trained COCO weights (mask_rcnn_coco.h5) from the releases page.

(Optional) To train or test on MS COCO install pycocotools from one of these repos. They are forks of the original pycocotools with fixes for Python3 and Windows (the official repo doesn't seem to be active anymore).

Linux: https://github.com/waleedka/coco
Windows: https://github.com/philferriere/cocoapi. You must have the Visual C++ 2015 build tools on your path (see the repo for additional details)
