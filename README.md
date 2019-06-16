# EE451-Image Analysis and Pattern Recognition Final Project
Team Member: Cai Fengyu, Zhou Wanhao, Sepehri Yamin

## Result
Report of the result on the test @IOU=0.3
1. detection by segmentation: 0.29
2. detection by sliding window and classifier: 0.23
3. detection by Mask-RCNN: 0.71

Report of the result on the competition
- Group Name: Group2
- Best F1 score: 0.734 (ranked 2nd place in the competation)


Sorry for the inconvenience that we have submissions from two team names: 'Group2' and 'Group2 Method3'. Please, just ignore the second one! Thank you so much!

# Environmental Requirement:
Packages:
- keras
- tensorflow
- skimage
- scipy
- sklearn
- numpy
Hardware:
- GPU Tesla K80 with 15G memory
- 12G memory provided by Colab

# Environmental Setup
- Get the module of Mask-RCNN from the github
    ```sh
    $ git clone --quiet https://github.com/matterport/Mask_RCNN.git
    $ cd Mask_RCNN
    $ pip install -q PyDrive
    $ pip install -r requirements.txt
    $ python setup.py install
    ```
- Get the [pretrained weight based on the coco dataset](https://drive.google.com/open?id=1-BrhVIEwkXY499A9lWJiFFhmmKPCEf-x)
- If you would like to skip the training process, you can also download our trained weights from [here](https://drive.google.com/open?id=1-s_USIMMwfwQAyhPP20E1dvH9NscgAvF)

# References:
1. Mask R-CNN for Object Detection and Segmentation， https://github.com/matterport/Mask_RCNN
2. Lecture Notes, EE451 Image Analysis and Pattern Recognition, Spring 2019
3. Watershedding algorithm, https://en.wikipedia.org/wiki/Watershed_(image_processing)
