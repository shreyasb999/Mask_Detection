# Mask_Detection


# Dataset : 

The dataset is small portion of publicly available dataset on Kaggle.

Training data consists of total 419 images of which 216 images belong to class "NO_MASK" and 203 images belong to class "MASK"

Test data consists of total 111 images of which 59 images belong to class "NO_MASK" and 52 images belong to class "MASK"


# Data Pre-processing :

The image data was first resized to 224 x 224 .
This data was annotated using "LabelIMG" tool.


# Model :

The model was trained by transfer learning.

Model used for training : SSD_Mobilenet_v1_coco
Epochs : 20000

# Evaluation Scores :

Following are the scores after 20000 epochs :

![eval_scores](.\Capture.png)

