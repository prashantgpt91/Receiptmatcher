# EagleView

# Intution

Facebook's detectron2 supports a huge variety of pre-built models. I have used Faster-RCNN

# Code Base

All code is picked from facebook's detectron2 repository for https://github.com/facebookresearch/detectron2

# Folder structure explanation

config: contains the config

| Folder | Purpoe              |
|------------------|-------------------|
| logs  | contains the training logs for detectron2 model. Left empty for now|
| notebooks  | contains the notebook for EDA |
| checkpoints | contains the checkpoints used for finetuning and frozen model. Have intentionally left it empty. |
| data | contains original data |

# Ask of assignment
Model name : Mask-RCNN
Links to dataset and framework https://github.com/facebookresearch/detectron2
Primary Analysis present in EDA.ipynb
Assumptions
Inference present in ObjectDetection_Person_car.py
Conclusion:

True Positive Rate for Person is 85%
True Positive Rate for Car is 87% 

Recommendations: 
	Train for more epochs
	Use Augmentation
	Label smoothing may lead to better accuracy in case of inaccurate annotations 




