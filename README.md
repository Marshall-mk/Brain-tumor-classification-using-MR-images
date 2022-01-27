# Brain-tumor-classification-using-MR-images
This repo contains all the source code for my brain tumor classification and segmentation web app using brain MR images. An ensemble model was used for the detection and classification phase, and a res-UNET segmentation model for the segmentation phase. A web app was built using the DASH python library. The final models were then converted into a .tflite model and was deployed on a raspberry pi. 


The task understanding, data preprocessing and visualization was done in [TheProject](TheProject.ipynb). 
Afterwards, model building and training was done in [TheEnsembleModel](TheEnsembleModel.ipynb). 
Training the segmentation model is as shown in [TheSegmentationModel](TheSegmentationModel.ipynb).
[ModelCombo](ModelCombo.ipynb) contains codes used to test the contribution of each model by trying out multiple model combination.
[ModelConversion](ModelConversion.ipynb) contains codes used to convert the tensorflow models to tensorflow lite models.
The web app and model deployment was created using the [raspberry](raspberry.py) file.

A preview of the app is as shown below
![The app preview](app view.jpg)
