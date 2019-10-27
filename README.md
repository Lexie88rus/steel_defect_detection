![image](https://github.com/Lexie88rus/steel_defect_detection/raw/master/assets/cover_large.png)
# Steel defect detection
Repository containing the materials for [Kaggle Steel Defect Detection competition](https://www.kaggle.com/c/severstal-steel-defect-detection).
The description of our whole team's [__36th place__ solution](https://www.kaggle.com/c/severstal-steel-defect-detection/discussion/114269#latest-658776) on Kaggle

## Repository Contents
1. [Notebook containing the EDA](https://github.com/Lexie88rus/steel_defect_detection/blob/master/steel-defect-detection-EDA.ipynb)
2. Notebooks containing the models:
   * a starter segmentation [model](https://github.com/Lexie88rus/steel_defect_detection/blob/master/steel_vgg_unet_starter.ipynb)
   * a high accuracy [EfficientNetB4 model](https://github.com/Lexie88rus/steel_defect_detection/blob/master/steel-efficientnetb4-unet.ipynb). 
3. Notebook containing the [model output analysis](https://github.com/Lexie88rus/steel_defect_detection/blob/master/model-output-analysis.ipynb)

## Modelling Facts

What worked:

   * :white_check_mark: EfficientNet4 architechture
   * :white_check_mark: Combined BCE and DICE loss function
   * :white_check_mark: RAdam optimizer
   * :white_check_mark: image augmentation pipeline
   * :white_check_mark: training on cropped pieces of images
   * :white_check_mark: IOU score to validate the model
   
What did not work for me:
   
   * :x: Lovasz loss
   * :x: weighted sampling

## Additional Links
1. Link to [EDA notebook on Kaggle](https://www.kaggle.com/aleksandradeis/steel-defect-detection-eda).
1. Link to [model output analysis notebook on Kaggle](https://www.kaggle.com/aleksandradeis/model-output-analysis).

